# 个人微型知识库

## Windows相关

### 环境

#### Powershell 刷新环境变量

```powershell
$env:Path = [System.Environment]::GetEnvironmentVariable("Path","Machine") + ";" + [System.Environment]::GetEnvironmentVariable("Path","User")
```
