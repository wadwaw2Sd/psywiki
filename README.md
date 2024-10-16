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

## 关于datas/wiki/xx.md的编写格式，必须使用markdown格式，如果你不会建议你直接写下来让我来修改，请不要乱提交！
<pre>
## 中文名 英文名

---

简单的介绍

| 结构 | <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Pregabalin.svg" alt="Pregabalin SVG" width="400"> |
| ----------- | :-----------: |
| CAS | 144-11-6  |
| 法律地位 | 处方药 |
| 药效起始时间 | x |
| 半衰期 | 3.3-4.1小时 |

## 药理学

---

#### 药效学

  填写

#### 药物代谢动力学
  
  填写

#### 新陈代谢
    
  填写
    
## 娱乐用途

> 所有的效果

  中枢神经系统：

  外周副作用：

  眼睛：

---

## 药物相互作用

---

* 联用的哟啊u我
  > 增加的效果
</pre>

## 关于
  官方Telegram机器人 @DrugDataBot，.md结尾的文件点开就能直接查看相关信息，建议关注机器人，防止仓库封禁后找不到新的仓库。
