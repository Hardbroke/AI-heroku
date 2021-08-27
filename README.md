# AI-heroku

**若需部署 iRay VLESS，请转到 [vless](https://github.com/Hardbroke/AIray-heroku/tree/vless) 分支。**

## 概述

本专案用于在 Heroku 上部署 AIRay WebSocket，在合理使用的程度下，本镜像不会因为大量占用资源而导致封号。

部署完成后，每次启动应用时，运行的 AIRay 将始终为最新版本

## 部署

### 步骤

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/Hardbroke/iray-heroku)

 回到专案首页，点击上面的链接以部署 AIRay

### 变量

对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `b4821af5-19e6-47e0-8033-33613a9dad14` | VMess 用户主 ID，用于身份验证，为 UUID 格式 |
| `AID` | `64` | 为进一步防止被探测所设额外 ID，即 AlterID，范围为 0 至 65535 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |
