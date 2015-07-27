title: win7下安装hexo后找不到命令
date: 2015-07-24 17:43:12
tags: hexo
---
在win下安装完nodejs,版本号v0.12.7，用npm安装hexo，版本v0.12.7，出现
`hexo: command not found `
我猜应该是找不到路径，设置了环境变量，Path再新增C:\Users\xxxx\AppData\Roaming\npm,依旧找不到命令，无奈最后只能把 nodejs安装目录\node_global下node_modules ,hexo ,hexo.cmd拷到nodejs安装根目录下才能用。网上查资料发现nodejs在win7有些问题，不知道有更好的解决方案没有？