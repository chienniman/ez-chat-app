# ez-chat-app
非常簡單、輕鬆上手的聊天室，前端使用laravel的blade模板，後端基於Workerman，websocket_channel.php用於廣播websocket server
## 架構
```
chat
├── resources
│   └── views
│       ├── chatroom.blade.php         # 聊天頁
|
├── websocket_channel.php              # 廣播伺服器 --8006 port 
├── websocket_server.php               # Websocket伺服器、心跳 --8005 port
├── start_for_win.bat                  # Windows 啟動檔
```


## 運行
![heartbeat1](https://user-images.githubusercontent.com/97031067/213724633-8d486d13-86f3-444f-b650-ed0ac92b928f.jpg)
![4f469c41-c731-43fd-a882-b3c2fa1b210e](https://user-images.githubusercontent.com/97031067/213725280-57743942-1c4b-4c77-bf4b-3c9d26ace2e4.gif)

```
chat
├── resources
│   └── views
│       ├── chatroom.blade.php         # 聊天頁
|
├── websocket_channel.php              # 廣播伺服器 --8006 port 
├── websocket_server.php               # Websocket伺服器、心跳 --8005 port
├── start_for_win.bat                  # Windows 啟動檔
```
