# mosdns-rules

## 说明
- 本配置配合`clash-rule`+`fake-ip`模式使用，实现`dns`控制的透明代理
- 主路由控制`DHCP`分配的`dns`服务器可实现分设备透明代理控制
- 此配置的国内转发策略比较激进只走`quic ali`
- 有需要请在`forward_cn`中添加其他解析服务器（如运营商`dns`等）
- 有一些其他网段的转发策略，如`dn11`，`dn42`，`hdu`等，不需要请删除

## 配置文件
在 releases 分支下