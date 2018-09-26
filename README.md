# python-
python 3.x 直接使用 utf-8编码  无需像pyhon2一样 指定 UTF-8编码
        #!/usr/bin/python
        # -*- coding: UTF-8 -*-
        print "你好，世界";
        
直接     print（‘你好世界’）

范围内求素数


start =int(input('请输入起始值'))
end1=int(input('请输入终值'))
n=0
while(start<=end1):
    j=2
    while(j<=start/2):
        if (start%j==0): break;
        j+=1
    if j>start/2:  print(start,'是素数');n=n+1
    start+=1
if start>end1:
    print("over,此范围内共有",n,"个素数")


