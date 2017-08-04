# 快捷设置阿里巴巴`iconfont`图标的工具类

##### 在开发中，我们开始越来越多地使用`iconfont`图标。

##### 苦受`iconfont`图标设置的**繁琐**困扰，我封装了这个快捷设置阿里巴巴`iconfont`图标的工具类。

### 使用方法：

- 项目中引入`LYIconfont.h`和`LYIconfont.m`文件
- 在需要设置`iconfont`图标的文件中引入`LYIconfont.h`头文件

### 调用方式：

- 获取一个`UIButton`类型的图标：
```
UIButton *iconfontBtn = [LYIconfont LYIconfontButtonWithFrame:frame code:@"\U0000e6e9" color:someColor size:25.0];
```
- 获取一个`UILabel`类型的图标：

```
UILabel *iconfontLabel = [LYIconfont LYIconfontLabelWithFrame:frame code:@"\U0000e6e9" color:someColor size:25.0];
```

  ​

