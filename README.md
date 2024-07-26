# fnf.foo
首次安装并同步项目遇到 
kotlin-dsl was not found in any of the following sources: （翻译过来是：在以下任何来源中都找不到 kotlin-dsl 插件）
错误日志： 
Plugin [id: 'org.gradle.kotlin.kotlin-dsl', version: '2.1.7'] was not found in any of the following sources:

* Try:
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.

* Exception is:
org.gradle.api.plugins.UnknownPluginException: Plugin [id: 'org.gradle.kotlin.kotlin-dsl', version: '2.1.7'] was not found in any of the following sources:

- Gradle Core Plugins (plugin is not in 'org.gradle' namespace)
- Plugin Repositories (could not resolve plugin artifact 'org.gradle.kotlin.kotlin-dsl:org.gradle.kotlin.kotlin-dsl.gradle.plugin:2.1.7')
  Searched in the following repositories:
    Gradle Central Plugin Repository
        at org.gradle.plugin.use.internal.DefaultPluginRequestApplicator.resolveToFoundResult(DefaultPluginRequestApplicator.java:221)
        at org.gradle.plugin.use.internal.DefaultPluginRequestApplicator.lambda$resolvePluginRequests$3(DefaultPluginRequestApplicator.java:147)
        at org.gradle.util.internal.CollectionUtils.collect(CollectionUtils.java:207)
        at org.gradle.util.internal.CollectionUtils.collect(CollectionUtils.java:201)
        at org.gradle.plugin.use.internal.DefaultPluginRequestApplicator.resolvePluginRequests(DefaultPluginRequestApplicator.java:145)
        at org.gradle.plugin.use.internal.DefaultPluginRequestApplicator.applyPlugins(DefaultPluginRequestApplicator.java:88)
        at org.gradle.kotlin.dsl.provider.PluginRequestsHandler.handle(PluginRequestsHandler.kt:48)
        at org.gradle.kotlin.dsl.provider.StandardKotlinScriptEvaluator$InterpreterHost.applyPluginsTo(KotlinScriptEvaluator.kt:194)
        at org.gradle.kotlin.dsl.execution.Interpreter$ProgramHost.applyPluginsTo(Interpreter.kt:397)
        at Program.execute(Unknown Source)
       

原因是 下载kotlin插件问题，
解决方法，增加梯子，Android studio 同步的时候增加本地代理。具体步骤如下：
1.购买梯子  每月不到6元
https://fnf.foo/auth/register?code=qK6M   这个是我的，可以通过这个注册，有一天免费时间；
梯子的使用教程：
  https://fnf.foo/user/tutorial?os=windows&client=v2rayN （windows）
  https://fnf.foo/user/tutorial?os=mac&client=clashx（mac）
  梯子设置完看不到节点列表
  记得到【商店】领取免费权限
![image](https://github.com/user-attachments/assets/e0f1732a-10ba-46bf-97fa-195125cdd796)

2.Android studio 设置代理 
![image](https://github.com/user-attachments/assets/62f23fb9-f0dc-4da6-8e66-d01f5bcc42ba)

3.设置好后 【try  again】  等着下载就可以了。
注意梯子有流量限制，免费的只有1G  
如图签到薅羊毛，可以增加点流量！
![image](https://github.com/user-attachments/assets/44daf7ee-8e54-4a36-9745-e1580b514804)



4.如遇gradle插件无法下载，可以尝试使用手机版本加速器。
扫描二维码 下载加速器。 加速器邀请码帮忙填写【  bHMsg   】感谢老铁，码字不易，薅点羊毛 ,弄点免费时长！
![image](https://github.com/user-attachments/assets/54bdb5f4-2172-4ad9-a469-5ce697dbbaa4)

https://6ef0.d95eddefe.com/
下载后点击连接，开启手机热点。电脑连接热点即可。可以和上面梯子混合使用！
如果仍然不可，尝试断开手机连接的WiFi使用数据流量（注意自己的流量套餐）
加速器有300m流量, 但！！！！开启热点给电脑，不消耗加速器流量！！！！
