***Writing Ahead**: This file is about the skills should be leart, including professional skills in computer science and AI, and other skills(or infomation, idea) in multi-media, ACG(Anime, Comic, Gaming), modeling, economic, and photography*

# Computer Science

## Git, a VCS(Version Control System)

- when using "git rm \<filename\>", and the file is modified both in staged area and workship, it worns: "error: the following file has changes staged in the index", maybe i missunderstand the usage of "git rm"?


## Learn about Vim

### **From the guaid: [Learn-Vim](https://github.com/iggredible/Learn-Vim/tree/master)**

### Starting Vim
When need to check a command's usage, please run `:h <comand>`. If you input the command and press `tab`, vim will show you relevant keywords.

vimrc is like a config file, usually named as .vimrc  

When run vim, please run at the nocompatible mode, beacuse in compatible mode, many Vim's features fail. Write `set nocompatible` in the .vimrc file.

You can open a vim window by run `vim -o<num>`, it will open \<num\> horizontal windows, while -O compose to vertical windows.
  
**Buffer**: a workshop of an opened file, you can treat it as a edit area of the file.  

Traverse buffers:
- `:bnext`, read as 'buffer next'
- `:buffer`
- `:buffern`, means jump to the n number buffer. For example, typing :buffer 2 will take you to buffer #2.
- press \<ctrl + O\> to jump to old buffer, \<ctrl + I\> to jump to new buffer.(This is buffer-specific methods)
- \<ctrl + ^\> to jump to previously edited buffer.
-   
Delete buffer: `:bdelete`

### About buffers and windows  
Buffer can be treated as the workshop of file.   
If you open the same file with two buffers, once you change it in a buffer, contents of the file will change with real time in another.

This is about windows split:
- <ctrl + w> is the prefix of windows split shortcut key.
- <ctrl + w + v>: split a new windows vertically
- <ctrl + w + s>: split a new windows horizontally
- <ctrl + w + c>: close the current split
- <ctrl + w + o>: remain the current split only
- <ctrl + w +h/j/k/l/>: move the cursor between splits

This is about windows:  
- `:split <filename>`: split a file horizontally
- `:vsplit <filename>`: split a file vertically
- `:new <filename>`: create a new window with a file(Some thing goes wrong there)

Remenber this: once you open a buffer, it will stay in buffer area except you close all the window and open it again.

### Tabs  

#### Brief  
Tabs is a kind of layout of file instead of file itself. When you close the tabs, it means you abandoned the layout, but the file opened will remain in the buffer area.

#### Command

`:tabnew <filename>` / `:tabclose`: close the current tab  
`:tabnext`  /  `:tabprevious`  
`:tabfirst` / `:tablast`  

You can open multi files with multi tabs using: `vim -p file1.js file2.js file3.js`, '-p' may mean parallel.

#### Shortcut key

Press \<gt\> to go to the next tab, \<gT> to the previous tab. 

Press \<3gt\> to the third tab

### Search in Vim

`:edit **/*.md<Tab>`  -> search recursively.


## Be familiar with Keyshot

### VScode
| 按键 | 效果 | 按键 |效果 |
|--- |---|---|---|
|ctrl + r|切换工作区|alt + z |切换自动换行（切换后可以看到完整的行）
|ctrl + g|转到行|ctrl + p |转到文件|
|F8|转到下一个错误或报告|ctrl + tab|切换选项卡（即已经从工作区打开的文件）|
|F2|重命名变量（似乎很有用）|ctrl + shift + o|open the menu of currently opened file|
|ctrl + 1|聚焦到编辑区第一栏|

### Windows
|按键|效果|按键|效果|
|---|---|---|---|
|alt + F4|关闭当前窗口|


## Ubuntu on VMware

具体教程参考b站[这里](https://www.bilibili.com/video/BV1EBXUBKErk/?spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=1d5be00f9f74e7a0445ca300d90db914)

## Learn about Script

## Learn about HTML and collect infomation from it

# AI

## Latex, a good helper for paper writer

## Science Computing

## Torch: deal with network

## Scikit-learn: a kpi for ML methord from Google

# Media record

## 账号发展的思路

定个小目标，在年末先攒到五千粉丝，有资格参加抖音创作者伙伴计划。

接下来先用《王者荣耀世界》吸引一部分人，然后用主要播《异环》。说实话异环这个设定和世界观挺讨人的欢的。

这几天把《哀鸿：城破十日记》的游玩体验先出几期视频再说吧。

## OBS usage 
### OBS设置有关的专业术语
通用；输出；音频；视频；无障碍环境配置；高级选项


1. How to set a screen source to OBS
2. 

## Ways to print the screen

## Live-show and its tools' usage

# Japanese

I think maybe i should learn to speak Japanese, to feel its culture better.


# ACG

## 异环

## 哀鸿；城破十日记

背景：弘光十年？
主角：兽视，将人看作走兽  
杨军爷   王生    绍兴女儿红（万历42年陈酿）  
花雕（凋）酒  
督师派兵进城，占了地方索要钱财  
广陵  
去年八月  兴平伯高杰进城被阻，遂施暴  
去年正月，李闯西安称帝，建大顺

主角和王生关系似乎不错？但为什么杨军长动怒的时候主角要那样揣测王生？    
主角将出门际被王生叫住，但他又推搡说没事  
去年欠了王生一百两银子？  
与女主五年前充分，四年前最为交好，女主三年前自杀  
主角记忆里女主尸体是在桥面上而不是湖面上？或许不是跳河自尽？  
督师想城破后一人受难，好像是好人，可是督师的兵在主角眼里印象不好  
主角居新城东头偏西  
老林头之前和主角认识，但现在他好衣换破衣的行为有古怪，看到主角就慌乱走开  
史督师掌管大明所有残存兵马，此时正自北向南逃跑  
兴平伯是西北出身？西北边兵？山野草莽？

1641，崇祯14年
主角关于《金瓶梅》的自省，认为自己在君子与小人之间，感觉有点闹麻  
主角关于自己工作的阐述，对女主的态度，让人感觉他是一个飞扬轻浮的人  
白甲妖怪是亲兵，最为尊贵，红蓝次之  
主角对王生这种有妻子的人的共情，该如何解读？是人之常情，还是别有深意？（我能问出这种问题感觉也有点闹麻了）  


### 第三章？好像是
崇祯五年（1632），闯兵入晋地，主角九岁，女主11岁，要被送往扬州？  （说是这是十三年前，那主角现在是22岁吧）  
主角原来也是大户人家呢，大伯在扬州，此时父母已经双双被杀？   
这一章看到了当时良离开后的鸢，正着手琼华回家的事。  
主角九岁，琼华九岁马上满十岁。  
女主给男主的第一印象太惊艳了。  

###  记，第三回
弘光元年（1645）

老林头叛变了，You son of b**ch   
红甲兵好像是低等兵，狼妖鹰妖好像也都是低等兵。  
十三年前雁儿带着主角逃，现在主角带着雁儿逃。  

### 记 第四回：逃生
史阁部被俘身死。主角被发现并逃命。  

### 记 第五回：破幻  
连雁在男主和空幻面前消失。  

主角十岁与女主相离，17岁重逢。  

狼兵似乎是闯军。  

章京大人？

### 记 第七回

女主是自杀，主角却对女主的死心有愧疚？林翩翩和女主似乎有联系？  




### 游戏选项：
十两，（要去观音庙躲房梁上面才有活路，有点难绷）。  



### 时间地点信息

1621，天启元年，女主生，两年后男主生；1627年，崇祯元年；1645年，弘光元年，扬州城破。

小秦淮河畔的城南街区，是广陵有名的风月之地（花街酒楼）。  

东城门，北城门，市集，张家巷，破庙。  



# Ecnomic

# Photography

# Mess Information
