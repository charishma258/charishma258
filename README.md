
amount=int(raw_input())
print "total bill is",amount
if(amount>=1000 and amount<=2000):
  c=(amount*10)/100
  print "Discount on the bill amount is",c
elif(amount>2000 and amount<=3000):
  c=(amount*20)/100
  print "Discount on the bill amount is",c  
elif(amount>3000 and amount<=5000):
  c=(amount*30)/100
  print "Discount on the bill amount is",c
elif(amount>5000):
  c=(amount*40)/100
  print "Discount on the bill amount is",c
print "amount to be paid",(amount-c)
#output
'''
6000
total bill is 6000
Discount on the bill amount is 2400
amount to be paid 3600
'''
