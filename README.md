# 个人微型知识库

## Windows相关

### 环境

#### Powershell 不重启刷新环境变量

```powershell
$env:Path = [System.Environment]::GetEnvironmentVariable("Path","Machine") + ";" + [System.Environment]::GetEnvironmentVariable("Path","User")
```

## Github

- [Octo Mate - Chrome 网上应用店](https://chrome.google.com/webstore/detail/octo-mate/baggcehellihkglakjnmnhpnjmkbmpkf/related)
