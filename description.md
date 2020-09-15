# 常见问题解决方法

### 未在本地计算机上注册“Microsoft.Ace.OLEDB.12.0”提供程序
+ 尝试从官方网址下载安装[Microsoft Access Database Engine 2010](https://www.microsoft.com/en-in/download/details.aspx?id=13255)（下载的软件位数需要和Office软件位数一致）

### 不能更新下载
+ 你可以**[点击这里](https://raw.githubusercontent.com/lsdyl/redbull_sjzx/master/RedBull_setup.exe)**自行下载
+ 可以通过代理网络来访问更新网站，或尝试修改Hosts，方法如下[^注1]：
1. 按 `Win+R`，打开运行
2. 输入 `%SystemRoot%\system32\drivers\etc\hosts`,回车
3. 选择打开方式为 记事本
4. 打开后在文档末尾添加新行，输入`151.101.108.133 raw.githubusercontent.com`[^注2]
5. 保存Hosts文档，退出

---











[^注1]:如果你可以轻松访问下载，则不需要此步骤
[^注2]:由于不确定原因，此IP地址可能会更改，所以可能需要定期修改