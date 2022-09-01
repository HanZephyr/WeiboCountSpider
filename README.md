# WeiboCountSpider

## 项目介绍
定时监测指定用户的博文数量，若用户微博数量发生变动，则会通过“爱语飞飞”平台发送微信通知


## 使用方式

通过命令行直接运行，需传入 uid 与 iyuu_token 两个参数。格式为：`python weiboCountSpider [用户微博ID] [iyuu_token]`

例：
```shell
python weiboCountSpider.py 123456 IYUU****************************************
```

> 注：iyuu_token 为 “爱与飞飞” 微信通知平台 TOKEN，需要通过“爱与飞飞”官网获得
> [爱语飞飞官网：https://iyuu.cn/](https://iyuu.cn/)

