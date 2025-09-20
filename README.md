num=int(input('enter a number:'))
temp=num
sum_fact=0
while temp!=0:
    d=temp%10
    fact=1
    i=1
    while i<=d:
        fact=fact*i
        i+=1
    sum_fact+=fact
    temp=temp//10
print(sum_fact)
if sum_fact==num:
    print('strong number')
else:
    print('not a strong number')
