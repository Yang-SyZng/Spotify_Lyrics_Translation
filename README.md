# Spotify非中文歌词翻译
# 沿用@app2simle的部分源代码！！
采用百度翻译接口进行翻译,需要先免费申请百度翻译api的id和密钥,然后根据不同软件进行不同配置

-----------申请百度翻译(有标准版和高级版 建议申请高级版)api--------------

标准版(很可能不够用):单次最长请求1000字符,免费调用量5万字符/月,QPS=1
高级版:单次最长请求6000字符,免费调用量100万字符/月,QPS=10

    注册百度翻译个人开发者: http://api.fanyi.baidu.com/register
    注册后如果需要认证可自行选择是否实人认证(高级版需要验证)
    开通(通用翻译)API服务: https://fanyi-api.baidu.com/choose
    成功后即可看到自己的appid和密钥(不要泄露给任何人): http://api.fanyi.baidu.com/manage/developer
