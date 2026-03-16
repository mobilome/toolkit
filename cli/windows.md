## Windows常用命令

### 增加系统更新时间

```shell
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings" /v FlightSettingsMaxPauseDays /t reg_dword /d 10000 /f
```

### 刷新远程桌面用户名和密码

```shell
runas /u:MicrosoftAccount\3298990@qq.com winver
```

