# past-code
修改历史记录
echo $ROS_DISTRO 查看ros版本

ssh-keygen -t ed25519 -C "你的GitHub邮箱@example.com"
# 1. 在后台启动 ssh-agent 进程
eval "$(ssh-agent -s)"
# 2. 将你刚刚生成的私钥添加进去
ssh-add ~/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub （查看复制公钥）


xhost +local:root
docker start jaka_humble_env   开启一个容器
docker exec -it jaka_humble_env bash  进入容器内部
多开终端，不用执行第一条图形化指令


rm -rf build install log
