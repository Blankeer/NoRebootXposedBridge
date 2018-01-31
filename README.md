# 免重启的 XposedBridge

参考: https://bbs.pediy.com/thread-223713.htm , 加了点自己的修改.

会降低性能,慎用,开发模块时在模拟器使用美滋滋.

1. 导入 as 
2. ReBuild
3. /app/build/outputs/apk/ 将 apk 重命名为 XposedBridge.jar
4. 手机替换掉 /system/framework/XposedBridge.jar
5. 重启手机
6. 检查日志是否加载正常,检查是否有 "start reload modules","finish reload modules" 的日志
