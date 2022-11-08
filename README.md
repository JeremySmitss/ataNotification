				  
				  **ataNotification  install Tutorial 安装教程!**
**This Script Are Standalone 此插件不需要任何前置 所有框架都可用.**

**1.从 [GitHub](https://github.com/YishengCheww/ataNotification) 上下载插件 , 将插件放入你的FiveM伺服器里**

**1.(ENG) Download ataNotification from [GitHub](https://github.com/YishengCheww/ataNotification)**

**2.将插件放入伺服器 并在你的server.cfg 里启动**

**2.(ENG) Drag & Drop the plugin to your server and start in server.cfg**

**3.至此插件安装成功**

**3.(ENG) the plugin are success installed**

**                                                        # How To Trigger 如何触发trigger**

**1.客户端 例子:  `exports['ataNotification']:notification('far fa-keyboard text-primary','Long text test',"This is long text test", "Halo How are u Now		", 15000,'not1') `**

**伺服器端 例子: `TriggerClientEvent('ataNotification:show', source, {
    sound = 'not1',
    icon = 'fas fa-exclamation-circle text-danger',
    title = 'title here',
    message = 'hello world',
    time = 7000,
    appname = 'Server'
})  `**

**1.(ENG) Client side tutorial : `exports['ataNotification']:notification('far fa-keyboard text-primary','Long text test',"This is long text test", "Halo How are u Now		", 15000,'not1') `**

**(ENG) Server side Tutorial: `TriggerClientEvent('ataNotification:show', source, {
    sound = 'not1',
    icon = 'fas fa-exclamation-circle text-danger',
    title = 'title here',
    message = 'hello world',
    time = 7000,
    appname = 'Server'
})  ` **

**2.添加新notify 方法: 	`exports['Atanotify']:Notification('ICON COLOR',appname,title, message , time ,sound)`**

	**`time = 5000 - 15000 good`**

	**`sound = default or not1 or not2 你可以添加新的音效到 html/sound`**

**2.(ENG)Add New Notify Pattern Tutorial : 	`exports['Atanotify']:Notification('ICON COLOR',appname,title, message , time ,sound)`**

	**`time = 5000 - 15000 good`**

	**`sound = default or not1 or not2 and you can add new sound to html/sound`**

**预览 PreView:**





![noti](https://user-images.githubusercontent.com/64354150/151497033-51ee0260-fd70-4f8a-9cb3-da96cee7f90f.png)
