### [中文][4]🇨🇳 | [English][5]🇬🇧
# Usage:
1. Download the path file that matches the version of your tool. For example, if you are using Version **2019.1.3**, please download  **jetbrains-agent-2019.1.3.jar**

2. Run the IDE and evalutate for free

3. Click IDE menu "Configure" or "Help" -> "Edit Custom VM Options..."
4. Append " -javaagent:/absolute path/jetbrains-agent-2019.X.X.jar " to end line
    eg:
    
      mac:      -javaagent:/Users/ifkid/jetbrains-agent-2019.X.X.jar
      
      linux:    -javaagent:/home/ifkid/jetbrains-agent-2019.X.X.jar
      
      windows:  -javaagent:C:\Users\ifkid\jetbrains-agent-2019.X.X.jar
5. Restart IDE (<font color=red>very import</font>)
6. Click IDE menu "Help" -> "Register..." or "Configure" -> "Manage License..."
Entry license server address: **http://jetbrains-license-server**  (maybe autofill)
        Or click the button: "Discover Server" to fill automaticly

# 使用方法:
 1. 先下载你的工具对应版本的补丁文件jetbrains-agent-2019.X.X.jar，把它放到你认为合适的文件夹内。例如，你的工具为2019.1.3版本，则选择jetbrains-agent-2019.1.3.jar下载；
 
 2. 启动你的工具，如果上来就需要注册，选择：试用（Evaluate for free）进入IDE；
 
 3. 点击你要注册的IDE菜单："Configure" 或 "Help" -> "Edit Custom VM Options ..."
    如果提示是否要创建文件，请点"Yes"；
 
 4. 在打开的vmoptions编辑窗口末行添加：-javaagent:/absolute path/jetbrains-agent-2019.X.XX.jar
    一定要自己确认好路径(不要使用中文路径，不要有空格)，填错会导致IDE打不开！！！最好使用绝对路径。
	一个vmoptions内只能有一个-javaagent参数。
    示例:
      mac:      -javaagent:/Users/neo/jetbrains-agent-2019.X.X.jar
      linux:    -javaagent:/home/neo/jetbrains-agent-2019.X.X.jar
      windows:  -javaagent:C:\Users\neo\jetbrains-agent-2019.X.X.jar

5. 重启你的IDE(<font color=red>非常重要</font>)
6. 点击IDE菜单 "Help" -> "Register..." 或 "Configure" -> "Manage License..."
    选择License server方式，地址填入：**http://jetbrains-license-server** （应该会自动填上）
        或者点击按钮："Discover Server"来自动填充地址。



 本项目只做学习研究之用，不得用于商业用途！
 
 若资金允许，请购买[正版][1]，谢谢合作！
 
 学生凭学生证可免费[申请][2]正版授权！
 
 创业公司可[5折购买] [3] 正版授权！

[1]:https://www.jetbrains.com/idea/buy
[2]:https://sales.jetbrains.com/hc/zh-cn/articles/207154369-学生授权申请方式
[3]:https://www.jetbrains.com/shop/eform/startup
[4]:https://github.com/ifkid/JetBrainsCrack/master/README.MD#使用教程
[5]:https://github.com/ifkid/JetBrainsCrack/master/README.MD#Usage
