Q:笔记本触控板没反应，设备管理器也没有怎么办？

A:设备管理器的人体学输入设备->I2C HIC设备->禁用设备，再重新启用，重启电脑即可~

Q:git怎么上传本地文件到github？

A:目前的push步骤和网上不太一样，因为2020年github为避免racism将master换成了main，所以这条命令也要改。。。
```
git clone https://github.com/用户名/repository名字.git
git add .
git commit -m 'hello, world'
git push -u origin main
```
接下来第一个弹窗输入用户名、密码；
第二个弹窗输入用户名、token（位于Settings/ Developer settings，40位）；
push成功
