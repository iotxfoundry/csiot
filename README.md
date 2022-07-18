# csiot
csiot trial issues

## 简介
IoTx 是一款基于 Go 语言开发的，支持单服务器和分布式集群的物联网接入平台。 
IoTx 是基于微服务的分层架构，为设备/节点和云/应用之间提供双向转换引擎。

## 版本

|版本|说明|
|---|---|
|Trial|免费试用版，单机版，只支持一个产品和10个设备。|
|SE|MQTT协议层，基本核心层|
|PRO|5种协议层(MQTT,HTTP,COAP,WEBSOCKET)，核心层(+物模型)|
|Ultimate|协议层接入层，核心层(+物模型)，设备接入层，国密协议支持|

## docker hub

https://hub.docker.com/repository/docker/csiot/iotx-foundry

## 开始

```bash
docker run -d -p 8080:8080 -p 1883:1883 --name iotx-foundry csiot/iotx-foundry
```
