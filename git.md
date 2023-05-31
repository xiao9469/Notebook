第一次使用git环境搭建

1、配置用户名

git config --global user.name "wangyaya"

![img](git/f57b4bf438cd4aeca327179b04e81f63.png)

如果已经创建用户名可以通过 git config --global user.name  来查看

![img](git/58980796e36f4b828cf586d0f654dad4.png)

 2、配置邮件地址

git config --global user.email  "xxx邮箱号"

![img](git/87298ed8000b43ba85e56e88be065285.png)

 如果已经创建邮箱号可以通过命令  git config --global user.email 查看

![img](git/89804134f65745189ff41a0faaebf749.png)

 三、使用git上传代码

1、新建一个文件夹，右键点击git Bash Here ，跳出终端命令窗

 2、输入 git  init  新建一个git 仓库文件夹

![img](git/b633688043d640b79b41a3660e6090ed.png)

 在建立完之后会在文件夹中出现  .git文件夹

![img](git/bf27e21d34774ab18c5173e67c783e65.png)

3、进入仓库添加远程地址（克隆github上项目地址）

![img](git/23458ad4eaea423aa5227b59aa928915.png)

 使用命令   git remote add origin  ×××   添加远程仓地址

![img](git/fe07300bccdb46aca1a15d530144303c.png)

 通过 git remote -v 查看远程仓是否关联成功

![img](git/b282d50508e14ee18d13031b3eb97d5b.png)

 4、进行代码提交

git add .   将新的代码问及那或修改后的文件添加到存储库中

![img](git/648a8fc8095c4943bba66abe50db80ac.png)

 git commit -m "对上传代码进行一些备注"

![img](git/981bbd25828a4b71a1c62f8baa5cd38a.png)

 git push origin   master   将代码上传至master分支（如果想要上传至其他分支需要修改分支名）


![img](git/503ef2bdf9d34150842b8ce83e5a2b81.png)