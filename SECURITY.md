# 安全说明

本仓库发布的是 **KM Flash Tool 的成品程序与文档**，不含源代码。

## 报告问题

如果发现程序存在安全问题（例如任意文件写入、路径穿越、校验绕过、远程加载被劫持等），请通过以下方式联系，不要直接开公开 issue：

- 邮箱：3343296030@qq.com
- 或在 [Issues](https://github.com/zts10086/kmf-toolkit/issues) 中只描述影响面，由维护者私信索取复现细节。

请附上：程序版本、Windows 版本、复现步骤、日志文本（执行日志 → 保存日志）。收到后会在确认修复的版本说明中致谢。

## 发布物校验

每个发行版本都提供 `SHA256SUMS.txt`。下载后请核对：

```powershell
Get-FileHash ".\KM Flash Tool_3.3.9.exe" -Algorithm SHA256
```

校验值不一致时请不要运行该文件，并从 Releases 页面重新下载。
