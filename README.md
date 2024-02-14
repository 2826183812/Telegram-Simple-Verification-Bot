# Telegram-Simple-Verification-Bot
Telegram 简易验证机器人 - 检测文字回答问题进群。

## 现有功能
- [x] 预先验证
- [x] 支持自定义问答
- [x] 支持多个答案
- [x] 每人下放单独的定制链接
- [x] 可自定义下放最大链接数量
- [x] 自定义黑名单 & 封禁提示
- [x] 记录回答
- [x] 记录消息到文件
- [ ] 自动备份

## 适配环境
- Python == 3.11.0
  - Python-Telegram-Bot == 20.8

## 简易使用

### 第一步

01. 将此项目克隆至本地。
```
git clone https://github.com/ahalpha/Telegram-Simple-Verification-Bot.git
```
02. 定位到项目目录。
```
cd Telegram-Simple-Verification-Bot
```
03. 安装环境。
```
pip install -r requirements.txt
```

### 配置

编辑 `configs.py` 文件。
01. 你需要在你的 Telegram 中通过 `@BotFather` 来创建一个属于你的机器人，然后获取它的 `TOKEN` ，将其替换至 `token = "TOKEN"` 里的 `TOKEN` 中。
```
# 你的机器人 TOKEN
token = "TOKEN"
```
02. 获取你所要验证群聊的 `群聊ID` ，你可以选择通过邀请机器人 `@getmyid_bot` 来得到指定群聊的 `群聊ID` 。
```
# 所验证群聊的ID
group_id = -1000000000000
# 你可以使用机器人 @getmyid_bot 获取群聊的ID
```
