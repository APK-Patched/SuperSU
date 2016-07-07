# SuperSU
破解 SuperSU.apk 方法

=================

应用名称：SuperSU.apk (超级用户管理)

应用包名：eu.chainfire.supersu

备注：此应用为免费版(限制功能)，需要另外购买Pro

破解方法：

① 首先，反编译 SuperSU.apk，然后反编译 classes.dex。

② 找到 eu/chainfire/supersu/Settings.smali 文件并打开，定位到如下代码：

	.method public static a(Landroid/content/Context;Z)Z
    .registers 7

    const/4 v4, 0x0  //将 0x0 修改为 0x1

    const/4 v3, 0x1

    if-nez p1, :cond_50

    sget-object v0, Leu/chainfire/supersu/Settings;->i:Ljava/lang/Boolean;


按照上述标注修改然后保存。

最后编译，然后安装 SuperSU Pro.apk 。破解完毕！

=================

【特别声明】

👉 不保证上述破解方法永久有效！ 
如果此应用开发者重新修改代码，那上述破解方法就失效！这你必须要清楚明白！

👉 开发者敲字母编写程序代码也不容易，如果你条件(不管是经济还是网络条件)允许，还是请通过 Google Play商店 支付美元购买原版APK应用！以支持开发者的开发工作。

👉 我破解是因为我没有上述那个条件。穷逼无美元的破解者一个。 如果你愿意，请捐赠以支持我的破解工作。

👉 如果你还有问题？请 <a href=https://github.com/APK-Patched/SuperSU/issues>在此</a> 提交你的问题。
