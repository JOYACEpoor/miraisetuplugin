# Thanks [LoliconApi](api.lolicon.app)
    关键词匹配搜索支持tag和keyword搜索
# 本插件支持[MiraiConsole权限系统](https://docs.mirai.mamoe.net/console/Permissions.html#%E5%88%A4%E6%96%AD%E6%9D%83%E9%99%90)配置
即本插件需要使用Console的权限系统进行权限配置才能使用
# commands

    (/)来点色图
    (/)来点 <keyword>
    (/)manage 
        setuon
        setuoff
        r18on
        r18off
# config.yml

    //撤回功能 1s-120s时会生效，其他数字则禁用
    recallTime: -1
    
    //以下为回复 留空时(即''，如下一)则禁用该回复
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
