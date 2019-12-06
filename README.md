运行app即可立即跳到辅助功能页面，选择开启"HongBaoTest"的辅助功能，然后打开微信的聊天界面即可看到提示语"找到wx的表情图标"

如果报错无法运行请修改根目录build.gradle的classpath为你自己能运行的项目版本

如果APP崩溃过或APP在开启辅助功能的时候进行覆盖安装，大概率会出现辅助功能直接无效的情况（就是"红包锁定中"这句话都出不来），重启手机即可（以后需要注意，这是Android的通病）

由于国内第三方厂商各种奇葩定制，demo可能会出现以下问题：

1.打开微信好友页看不到提示语，解决方法以下几种：

    ①一键清理所有的app（包括demo），重新运行app

    ②上述操作无效的话，重启手机，重新运行app

    ③上述操作依然无效的话，可能是第三方厂商屏蔽了Toast，请开启悬浮窗权限（华为最奇葩的定制）或者直接查看Logcat的日志打印

2.手势发送失败：重启手机即可

辅助功能出问题万能解决方式：重启手机、debug、看日志