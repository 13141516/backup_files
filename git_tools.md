git与github:
=========================
git部分:
-------------------------
1.git init                                                  //创建local repository</br>
2.git add                                                  //添加工作区文件到暂存区</br>
3.git commit                                              //提交工作区文件到local repository</br>
4.git remote add xxx git@github.com:13141516/xxx.git     //local repository与remote repository建立联系</br>
5.git push -u xxx master                                //推送local repository到remote repository，且local master与remote master 建立联系</br>
6.git push xxx master                                 //推送到remote master</br>
7.git branch(查看分支)、git branch name(创建分支)、git checkout name(切换分支)</br>
8.分支工作：master:git branch --track master xxx/yyy,完成本地合并，提交。dev:与之前的master类似</br>
MarkDown语法演示：
------------------------
大标题
===================================
  大标题一般显示工程名,类似html的\<h1\><br />
  你只要在标题下面跟上=====即可

  
中标题
-----------------------------------
  中标题一般显示重点项,类似html的\<h2\><br />
  你只要在标题下面输入------即可
  
### 小标题
  小标题类似html的\<h3\><br />
  小标题的格式如下 ### 小标题<br />
  注意#和标题字符中间要有空格

### 单行文本框
    这是一个单行的文本框,只要两个Tab再输入文字即可
        
### 多行文本框  
    这是一个有多行的文本框
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可

### 链接
[点击这里你可以链接到www.google.com](http://www.google.com)<br />

###只是显示图片
![image](http://github.com/13141516/repository/raw/master/...)


### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>
    

