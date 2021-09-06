# 使用说明

# 浏览器中打开指定的应用程序

## 原理：

1. 在系统注册表中添加一个任意开头的协议名称，如 `twopener`
2. 给这个协议指定一个响应程序
3. 导入到注册表中之后，浏览器中通过请求指定开头的协议路径，如 `twopener://` 就会打开对应的程序

点此下 [载例子注册表文件](https://raw.githubusercontent.com/KyleBing/windows-app-opener/master/twoponer.reg)，双击导入到系统中后，再点击下面的链接就能直接打开 Windows 文件管理器了
