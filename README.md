<div style="text-align:center" markdown="1">
<img src="https://github.com/VernonVan/PPRoundedAvatar/raw/master/images/banner.png" width = 1000 alt="PPRoundedAvatar"/>
</div>

<font size = 4>PPRoundedAvatar——支持**异步裁剪**的圆角头像控件。  </font>
<div align=center> 
<img src="https://github.com/VernonVan/PPRoundedAvatar/raw/master/images/show.jpeg"  width=280  alt="效果演示"/>
</div>

## 主要功能
- [x] 圆角
- [x] 异步裁剪
- [x] 技术文章

## 使用

```objective-c
PPRoundedAvatar *avatar = [[PPRoundedAvatar alloc] initWithFrame:CGRectMake(0, 0, 100, 100)];
avatar.avatarImage = [UIImage imageNamed:@"example.png"];       // 头像图片
avatar.borderWidth = 1.0;                                       // 边框宽度
avatar.borderColor = UIColor.blackColor;                        // 边框颜色
avatar.borderHidden = NO;                                       // 显示边框
avatar.imageBackgroundColor = UIColor.grayColor;                // 背景颜色
[self.view addSubview:avatar];
```

## 安装
#### Cocoapods
1. 在podfile中添加 ```pod PPRoundedAvatar```
 2. 执行 ```pod install``` 或者 ```pod update```
2. 导入头文件 ```#import "PPRoundedAvatar.h"```  

#### 手动安装

1. 下载 PPRoundedAvatar 文件夹内的所有内容

2. 将目录下的 PPRoundedAvatar 目录添加（拖放）到你的工程中

3. 导入头文件 ```#import "PPRoundedAvatar.h"``` 

## 相关文章
[PPRoundedAvatar-高性能的异步裁剪圆角头像控件](https://vernonvan.github.io/2017/04/01/PPRoundedAvatar-%E9%AB%98%E6%80%A7%E8%83%BD%E7%9A%84%E5%BC%82%E6%AD%A5%E8%A3%81%E5%89%AA%E5%9C%86%E8%A7%92%E5%A4%B4%E5%83%8F%E6%8E%A7%E4%BB%B6/)

[ruanpapa和又吉君的日常之一(花絮)](https://vernonvan.github.io/2017/04/01/ruanpapa%E5%92%8C%E5%8F%88%E5%90%89%E5%90%9B%E7%9A%84%E6%97%A5%E5%B8%B8%E4%B9%8B%E4%B8%80/)

## 致谢
最后，感谢我的首席私人高级设计师--@又吉君🍻🍻🍻将这个开源控件从工科男的审美中挽救了回来。未来请你多多指教~
<p align="right">from: 你的ruanpapa</p>

   ​

   ​

   ​

   ​