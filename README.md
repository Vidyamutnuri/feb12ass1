# feb12ass1
yippe= 50
Oil=90
Surf=80
Biscuit=40
Bread=50
Chocolate=80
Cname=input('Enter customer name:')
Cphno=int(input('Enter customer phone number:'))
Y=int(input('Enter no.of yippee packages'))
O=int(input('Enter no of Oil packages'))
S=int(input('Enter no Of Surf pakages '))
B=int(input('Enter no of Biscuit pakages'))
B=int(input('Enter no of bread packages'))
C=int(input('Enter no of chocolates'))
cc=input('Enter Coupon code')
bill=(yippee*Y)+(Oil*O)+(Surf*S)+(Biscuit*B)+(Bread*B)+(Chocolate+C)
if bill>= 5000:
   cc=='Apple'
   dis=bill*10/100
   tax=bill*10/100
if  bill>=3000:
    cc=='Banana'
    dis=bill*8/100
    tax=bill*10/100
if bill>=2000:
    cc=='Orange'
    dis=bill*5/100
    tax=bill*12/100
if bill>=1000:
    cc='mango'
    dis=bill*3/100
    tax=bill*12/100
else:
    print('Invalid coupon code')
Mainbill=bill-dis+tax
print('bill amount:',Mainbill)
