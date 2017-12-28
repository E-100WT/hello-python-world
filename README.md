# hello-python-world
python!  python!!  python!!!
hello everyone in python-world !
我是一个新手，我希望在python中有进步！

计算个人所得税（练习）：









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


