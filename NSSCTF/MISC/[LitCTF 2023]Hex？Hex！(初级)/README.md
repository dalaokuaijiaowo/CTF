> Problem: [[LitCTF 2023]Is this only base?](https://www.nssctf.cn/problem/3968)

## 思路
* 解题大致思路
1.base64==一般放在最后，
尝试使用凯撒密码或栅栏密码

2.提示23，解SWZxWl=F=DQef0hlEiSUIVh9ESCcMFS9NF2NXFzM

3.找个网站，栅栏密码解码栏数23
w型得
SWZxWlFDe0liUV9ScF9FNFMzX2NSMCEhISEhfQ==

再base64解码
得IfqZQC{IbQ_Rp_E4S3_cR0!!!!!}

再凯撒密码
得
LitCTF{LeT_Us_H4V3_fU0!!!!!}
## EXP
* 具体攻击代码

## 总结
* 对该题的考点总结
栅栏密码 凯撒密码 base