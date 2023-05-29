# Home PortalWeb

## 使用方式
在 Release 中下载最新的压缩包，解压到 `C:\` 然后双击 `index.html` 即可。

建议将此页面设置为浏览器的 **主页** 和 **新标签页**。

## 开发和部署
```bash
git clone git@github.com:baobao1270/elders-portal.git
cd elders-portal
hugo server

# Generate static files
hugo -D --gc --minify --cleanDestinationDir
```
