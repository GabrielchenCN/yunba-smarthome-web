##云巴智能小屋demo
- web端控制页面

###安装

- git clone


###配置

- 修改main.js中config配置

    `var config = {
      APPKEY: '563c4afef085fc471efdf803',
      TOPIC: 'smart_home_topic',
      ALIAS: 'pi_house',
    }`
    
    其中APPKEY为你在 [云巴](yunba.io) 所建应用的AppKey；TOPIC为上报消息的Topic；ALIAS为云巴小屋的别名；请与 config.py 中保持一致。

###运行

- 完成硬件安装,[详见](https://github.com/yunbademo/yunba-smarthome)
- 开打html/index.html
