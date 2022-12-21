# Day-9_Disarium-number


def disarum():
    num=int(input())
    sum1=0
    product=1
    for i in str(num):
        c=int(i)**product
        sum1=sum1+c
        product+=1 
    if(sum1==num):
        print("True")
    else:
        print("False")
disarum()
