git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:hesidf/bash.git
git push -u origin master

cd -
cd $OLDPWD

Tab 快速补全


Ctrl+d 结束输入或退出shell	Terminate input, or exit shell

Ctrl+z 将正在运行的程序送到后台.  Suspend foreground process
“fg”、“bg”和“stop”等命令时，如果不加任何引号，则所变动的均是当前任务。
jobs -l
bg %1
----  后台进程的终止：
一：通过jobs命令查看job号（假设为num），然后执行kill %num   eg: $ kill %1
二：通过ps命令查看job的进程号（PID，假设为pid），然后执行kill pid  $ kill 5270
----  前台进程的终止：ctrl+c
Ctrl+c 结束正在运行的程序	Kill foreground process

Ctrl+s 暂停屏幕输出【锁住终端】 Suspend output

Ctrl+q 恢复屏幕输出【解锁终端】Resume output

Ctrl+l 清屏，【是字母L的小写】等同于Clear

Ctrl+a 切换到命令行开始

Ctrl+e 切换到命令行末尾

Ctrl+u 清除剪切光标之前的内容

Ctrl+k 清除剪切光标及光标之后的内容
Ctrl+y 在光标处粘贴剪切的内容
Ctrl+r 查找历史命令【输入关键字，就能调出以前执行过的命令】

Ctrl+t 调换光标所在处与其之前字符位置，并把光标移到下个字符
Ctrl+x+u 撤销操作





vi:
()""''成对的
for(i=0;i<-j;i++){...}
ci{  成对里的内容change
ca{ 成对里的内容 包括括号

ma
y'a


