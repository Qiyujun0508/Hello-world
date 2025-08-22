# Hello-world
此存储库用于练习 GitHub 流


登录不了github的解决方案：
1. ping github.com ，查到github.com的ip （例如查到的是：20.205.243.166） 
2. 修改hosts，所在目录为：C:\Windows\System32\drivers\etc\hosts
   注意：一定要先以管理员身份打开vscode 或者记事本，然后在通过打开命令打开hosts文件。否则hosts文件无法修改保存
3. 在hosts文件后的空行中加入n一行："20.205.243.166 github.com" (注意只加入引号中的内容，不包括引号)
4. 在cmd中运行 ipconfig/flushdns
显示如下：
Windows IP 配置
已成功刷新 DNS 解析缓存。
5. 完毕
