# Thanks [LoliconApi](api.lolicon.app)
    关键词匹配搜索支持tag和keyword搜索
    使用方式见config.yml
# 为简化命令 v1.5.3版本色图数量改为roll(1-10)点随机决定
# config.yml
    //匹配的命令 注意使用正则表达式 非必要可以不修改
    command: '来点(.*)色图'
    //反代地址，非代理地址，非必要不要修改
    proxyAddress: i.pixiv.re
    
    //以下均为回复 留空时则禁用该回复
    //启用或关闭色图功能的命令
    setuOnCommand: 开启色图
    setuOffCommand: 关闭色图
    //启用或关闭r18功能的命令
    r18OnCommand: 开启r18
    r18OffCommand: 关闭r18
    //匹配到命令开始搜索时bot的回复
    startSearchingReply: ''
    //匹配到命令但禁止色色时bot的回复
    refuseReply: 不可以色色！
    //启用或关闭色图功能的回复
    setuOnReply: 已开启色图
    setuOffReply: 已关闭色图
    //启用或关闭r18功能的回复
    r18OnReply: 已开启r18
    r18OffReply: 已关闭r18
    //没有搜索到结果时的回复
    noMatchResultReply: 你的xp好怪。。。
    //无法连接上LoliconApi时的回复
    connectionFailureReply: ''
    
    //撤回功能 1s-120s时会生效，其他数字则禁用
    recallTime: -1
    //bot主人qq号填写在这里 可以在没有群管理的情况下进行管理
    botOwnerId: 
      - 123456
      - 334455
