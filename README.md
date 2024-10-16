## 修改wiki_datas.json的须知

每个词条必须按以下格式修改

id填写的是我们这里wiki的识别id我会亲自修改

names填写的是触发词，第一个必须是id，第二个必须是英文名，第三个必须是cas，剩下的随便

wiki是用来指定我们的wiki，也就是datas/wiki里的.md结尾的文件，如果文件的内容为空请留空，如果有内容则填入github

odwiki是用来填写对应的odwiki的网站，如果没有对应词条请留空

psywiki是用来填写对应psywiki的网站，如果没有对应词条请留空

    "id": "词条id",
    "names": ["关键词1", "关键词2"],
    "wiki": "",
    "odwiki": "",
    "psywiki": ""

## 关于同步我们官方的数据

当你修改完wiki_datas.json后必须创建对应的我们的官方的文件，比如id为右美沙芬

在datas/wiki/里创建（右美沙芬.md） 如果你有能力可以帮我们编写内容，内容必须已经markdown格式编写

在datas/wiki/shorts/里创建右美沙芬 按照telegram官方支持的HTML格式编写

## 关于datas/wiki/xx.md的编写格式

## 关于
  官方Telegram机器人 @DrugDataBot，.md结尾的文件点开就能直接查看相关信息，建议关注机器人，防止仓库封禁后找不到新的仓库。
