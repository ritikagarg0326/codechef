# codechef #lonchallenge #August #2021
#By#RitikaGarg
t=int(input())
for i in range(t):
    g1,s1,b1,g2,s2,b2=map(int,input().split())
    sum1=g1+s1+b1
    sum2=g2+s2+b2
    if sum1>sum2:
        print("1")
    else:
        print("2")
