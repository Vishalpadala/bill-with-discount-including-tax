# bill-with-discount-including-tax
biryani_masalas=50
 
oil=140
 
dal=135 

rice=1250
 
salt=20 

Cname=input ("enter customer name: ") 

Cphno=int(input("enter customer number: "))

bm=int(input("enter number of Biryani masalas: ")) 

oils=int(input("enter no of oil packets:")) 

dals=int(input("enter no of dal packets: ")) 

riceb=int(input("enter number of rice bags: ")) 

saltp=int(input("enter number of salt packets:")) 

bill=(biryani_masalas*bm)+(oil*oils)+(dal*dals)+(rice*riceb)+(salt*saltp) 

if bill>5000:     
disc=bill*10/100     
print('discount',disc)  

elif bill>3000:    
disc=bill*8/100    
print('discount',disc)  

elif bill>2000:     
disc=bill*5/100     
print('discount',disc)  

elif bill>1000:     
disc=bill*3/100     
print('discount',disc)  

else:     
print('no discount available') 

if bill>3000:     
tax=bill*10/100 

else:     
tax=bill*18/100  

Main_bill=bill-disc+tax 

print("bill amount",Main_bill)
