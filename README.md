# PalServer-Daemon-Process
因為 [palserver GUI](https://github.com/Dalufishe/palserver-GUI) 0.2 的自動重啟很久沒做成，所以項目就產生了。
- 易於上手，只需放在palserver-GUI.exe同一文件夾`打開bat文件`即可啟動守護。
- 如果你伺服器性能較好，把targetUsage=20調得更低。意思是CPU使用率連續10秒低於20%，則判斷伺服器已經崩了。
