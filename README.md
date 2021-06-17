# chat-websocket

分布式多人聊天室

![luna-chat-2](./img/luna-chat-2.png)

![luna-chat](./img/luna-chat.png)

```
docker run -d \
    -p 8003:8003 \
    --name luna-post \
    --privileged=true \
    --restart always \
    luna-chat
```