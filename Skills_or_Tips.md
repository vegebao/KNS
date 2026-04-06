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

## 洛克王国：世界

## 异环

## 明末：渊虚之羽

## 文明六

# Ecnomic

# Photography

# Mess Information
