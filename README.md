修改客户端代码中的信令服务器地址。在 ./client/.env.production 中修改 VITE_SIGNAL_SERVER_URL 为您刚刚部署的信令服务器地址。

修改客户端代码中的 STUN 和 TURN 服务器地址。如果您额外部署了 STUN 和 TURN 服务器，您可以在 ./client/src/const.ts 中修改 iceServers 为您自己的 STUN 和 TURN 服务器地址。
