lan play

# 電腦端設定
1. http://www.lan-play.com/download 下載 LAN play client
2. https://github.com/takashi1kun/lan-play-GUI/releases 下載LAN play GUI, 需要在setting 中指定 lanplay.exe 的所在位置
3. http://www.lan-play.com/ 找一個適合的 public server。  台灣的應該比較順暢(switchlanplay-tw.ddns.net:11451)
4. 連線 start

# Switch 端設定
1. 連上與PC 同一個網段
2. ip 設定 ：
````cpp
IP Address Settings
IP Address: 10.13.XX.YY
Subnet Mask: 255.255.0.0
Gatewway: 10.13.37.1

DNS settings
Primary DNS: 163.172.141.219
Secondary DNS: 207.246.121.77
````
3. (大氣層)到 Kosmos Toolbox -> background service -> ldn_mitm-> ON
4. (SX OS) 到 Options -> internet local wireless play -> ON
5. 開遊戲，就可以玩囉

