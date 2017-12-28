# hello-python-world
python!  python!!  python!!!
hello everyone in python-world !
我是一个新手，我希望在python中有进步！

计算个人所得税（练习）：
个人所得税计算公式  
= 应纳税所得 = 工资总额 - 3500 - 五险一金    五险一金=0
 所得税 = 应纳税所得 * 对应的税率 - 数算扣除数
  
   应纳税所得    税率   扣除数           
   0 --- 1500    3%     0
   1500- 4500    10%    105
   4500--9000    20%    555
   9000--35000   25%    1005
   35000-55000   30%    2755
   55000-80000   35%    5505
   80000--->     45%    13505

a=float(input("输入数字："))
if a>=3500:
    a=a-3500
    if 0<a<=4500:
        a=a*0.03-0 if 0<=a<=1500 else a*0.1-105
    elif 4500<a<=35000:
        a=a*0.2-555 if 4500<a<=9000 else a*0.25-1005
    elif 35000<a<=80000:
        a=a*0.3-2755 if 35000<a<=55000 else a*0.35-5505
    else: 
        a=a*0.45-13505
else: 
    a=0
print("所得税＝",a)


计算标准体重

a=int(input("mam,1;woman,2:"))
h=int(input("身高:"))
b=(h-80)*0.7 if a==1 else (h-70)*0.6
print("标准体重＝",b,)

计算矩形周长，面积
while True:
    a=int(input("距形长:")) 
    b=int(input("距形宽:")) 
    c=(a+b)*2              
    s=a*b                  
    print("周长＝",c,"面积＝",s)
  
输入4个整数，输出最大的和最小的
  

a=int(input("输入数字："))
b=int(input("输入数字："))  
c=int(input("输入数字："))  
d=int(input("输入数字："))
max1=a if a>b else b
max2=c if c>d else d
max=max1 if max1>max2 else max2 
min1=a if a<b else b
min2=c if c<d else d
min=min1 if min1<min2 else min2
print(max,min) 
  
  
  
    




