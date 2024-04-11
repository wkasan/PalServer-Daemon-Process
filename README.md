# PalServer-Daemon-Process
因為 [palserver GUI](https://github.com/Dalufishe/palserver-GUI) 0.2 的自動重啟很久沒做成，所以項目就產生了。
- 易於上手，只需放在palserver-GUI.exe同一文件夾`打開bat文件`即可啟動守護。
- 如果你伺服器性能較好，把targetUsage=20調得更低。意思是CPU使用率連續10秒低於20%，則判斷伺服器已經崩了。

Because the automatic restart of [palserver GUI](https://github.com/Dalufishe/palserver-GUI)  0.2 has not been completed for a long time, the project was born.
- Easy to get started, just open the bat file in the same folder as palserver-GUI.exe to start the daemon.
- If your server has better performance, adjust targetUsage=20 lower. This means that if the CPU usage is lower than 20% for 10 consecutive seconds, the server is judged to have crashed.
