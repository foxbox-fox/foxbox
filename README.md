用afei项目:linbox 对其进行一定程度的压缩和删减，同时做一些个人优化。不喜欢请支持正主Afeimod 感谢mobox开发人员，darkos的支持，感谢咔咔龙，Afei，Asai，deemo等大佬支持和指导

下载所有文件，放在/sdcard/目录下，termux执行bash /sdcard/foxbox.sh文件，然后就可以一键安装了

proot的用户密码是2580，默认不输入密码

如果要在普通ternux使用，请执行 apt remove termux-x11-nightly -y pkg update -y pkg install x11-repo -y pkg install root-repo -y pkg install termux-x11-nightly -y 这是必要的过程，因为我更多使用云佬整合终端

foxbox
利用ssh链接termux+proot环境的glibc运行wine来转椅exe文件，并可以在Linux操作系统环境下运行
这是一个完全免费的开源项目，复制了Afei的linbox。我个人理解并修改了它，使它成为一个开放和自由构建打造环境的proot环境
Here, you have complete freedom to build your favorite Linux environment, and if you have the basics, you can even use chroot to customize your desktop
