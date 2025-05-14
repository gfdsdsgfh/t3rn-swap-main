
```bash
wget -O bridge-bot.sh https://raw.githubusercontent.com/gfdsdsgfh/t3rn-swap-main/main/bridge-bot.sh && chmod +x bridge-bot.sh && ./bridge-bot.sh

请先运行以下命令来创建新容器（使用新名字）：docker run -itd --name crosschain -v /Users/ashuai168/Desktop/t3rn-swap-main:/app -e TG_USER_ID=123456 ubuntu:latest

执行成功后，你再进入容器：docker exec -it crosschain2 bash
进去之后你会在容器的 /app 目录看到你本地的 t3rn-swap-main 项目。然后你可以：cd /app




查看目录中的文件，确认 bridge-bot.sh 是否存在：ls


添加执行权限：chmod +x bridge-bot.sh


运行脚本：./bridge-bot.sh
