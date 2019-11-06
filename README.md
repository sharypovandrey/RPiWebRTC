# RPiWebRTC

### Kill proccess of streaming
`kill -9 $(ps -ef | awk '/[m]eet.jit.si/{print $2}')`

### Launch Jitsi website and start to strem
`DISPLAY=:0 nohup /usr/bin/chromium-browser --noerrdialogs --disable-session-crashed-bubble --kiosk https://meet.jit.si/mr_freeman_x &`