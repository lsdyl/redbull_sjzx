# 常见问题解决方法

### 软件提示：未在本地计算机上注册“Microsoft.Ace.OLEDB.12.0”提供程序
- 尝试从官方网址下载安装[Microsoft Access Database Engine 2010](https://www.microsoft.com/en-in/download/details.aspx?id=13255)（下载的软件位数需要和Office软件位数一致）

### 安装成功后无法运行
- 本软件依赖于.NET Framework 4.5和Visual Studio 2010 Tools for Office Runtime，你可以尝试从[微软官方网站](https://www.microsoft.com/zh-cn/)下载安装依赖：
    - [点击这里](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net45-web-installer)下载安装.NET Framework 4.5
    - [点击这里](https://www.microsoft.com/en-us/download/confirmation.aspx?id=48217)安装Visual Studio 2010 Tools for Office Runtime

### 软件不能自动更新下载
- 你可以**[点击这里](https://raw.githubusercontent.com/lsdyl/redbull_sjzx/master/RedBull_setup.exe)**自行下载安装
- 可以通过代理网络来访问更新网站，或尝试修改Hosts，方法如下[^注1]：
    1. 按 `Win+R`，打开运行
    2. 输入 `%SystemRoot%\system32\drivers\etc\hosts`,回车
    3. 选择打开方式为 记事本
    4. 打开后在文档末尾添加新行，输入`151.101.108.133 raw.githubusercontent.com`[^注2]
    5. 保存Hosts文档，退出

######  如有任何意见或建议，请联络我
---











[^注1]:如果你可以轻松访问下载，则不需要此步骤
[^注2]:由于不确定原因，此IP地址可能会更改，所以可能需要定期修改