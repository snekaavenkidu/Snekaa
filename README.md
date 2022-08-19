# Snekaa
#program 1
onekgonion=20  #initialze onion value
onekgtomoto=10.5 #initialize tomoto value
budget=float(input("enter budget value:\n")) #read budget value
product=int(input("enter the product 1--- onion, 2-- tomoto:\n"))
if product==1:
    o=int(input(" \nenter how many kg of onion:"))
    amount=o*onekgonion
else:
     t=int(input(" \nenter how many kg of tomoto:"))
     amount=t*onekgtomoto
if amount<=budget:
    print("you can buy things")
else:
    print("you cannot buy. No budget")


#program 2

budget=float(input("enter budget value:\n")) #read budget value
onion=int(input("enter how many kg of onion you need"))
city=int(input("enter the city 1--- chennai, 2-- trichy    3--- madurai:\n"))
if city==1:
    amount=onion*30
elif city==2:
     amount=onion*27
else:
    amount=onion*34
if amount<=budget:
    print("you can buy things. budget amount is:")
else:
    print("you cannot buy. No budget")
    
    
    
program 3

rsofonecake=20
sellingcake=40
rsofonebread=10
sellingbread=15
noofemployee=2
totalprofit=0
for i in range(0,3):
    buycakeorbread=int(input("enter the options of customer 1-- cake, 2--- bread"))
    if buycakeorbread==1:
        noofcake=int(input("\nenter how many cake you want:"))
        sellingprice=noofcake*sellingcake
        costprice=noofcake*rsofonecake
        profit=sellingprice-costprice
        print(("customer {}  amount {}".format(i,sellingprice)))
    else:
        noofbread=int(input("\nenter how many bread you want:"))
        breadamount=noofbread*sellingbread
        sellingprice=noofbread*sellingbread
        costprice=noofbread*rsofonebread
        profit=sellingprice-costprice
        print(("customer {} amount {}".format(i,sellingprice)))
    totalprofit=totalprofit+profit
employee_pay=noofemployee*100
profitof_oneday=totalprofit-employee_pay
print("Profit of shop A is {}",format(profitof_oneday))


#CAKE LIMIT
rsofonecake=20
sellingcake=40
rsofonebread=10
sellingbread=15
noofemployee=2
totalprofit=0
cakelimit=1000
breadlimit=1000
for i in range(0,3):
    buycakeorbread=int(input("enter the options of customer 1-- cake, 2--- bread"))
    if buycakeorbread==1:
        noofcake=int(input("\nenter how many cake you want:"))
        if noofcake<=cakelimit:
            cakelimit=cakelimit-noofcake
            sellingprice=noofcake*sellingcake
            costprice=noofcake*rsofonecake
            profit=sellingprice-costprice
            print(("customer {}  amount {}".format(i,sellingprice)))
        else:
            print("\ncake is not in stock")
    else:
        noofbread=int(input("\nenter how many bread you want:"))
        if breadlimit<=noofbread:
            breadlimit=breadlimit-noofbread
            breadamount=noofbread*sellingbread
            sellingprice=noofbread*sellingbread
            costprice=noofbread*rsofonebread
            profit=sellingprice-costprice
            print(("customer {} amount {}".format(i,sellingprice)))
        else:
            print("\n Bread is not in stock")
    totalprofit=totalprofit+profit
employee_pay=noofemployee*100
profitof_oneday=totalprofit-employee_pay
print("Profit of shop A is {}",format(profitof_oneday))


#wedding expense
lunch_cost=250
cost_breakfast=250/2
noofperson=int(input("enter the no of person:"))
lunch_amount=noofperson*lunch_cost
breakfast_amount=noofperson*cost_breakfast
cost_hall=lunch_amount*1/3
cost_decoration=cost_hall*50/100
cost_parking=cost_hall*10/100
total_expenses=lunch_amount+breakfast_amount+cost_hall+cost_decoration+cost_parking
print("WEDDING EXPENSES")
print("Cost of Hall : {}".format(cost_hall))
print("Cost of Decoration : {}".format(cost_decoration)) 
print("Cost of Lunch : {}".format(lunch_amount))
print("Cost of Breakfast : {}".format(cost_breakfast))
print("Cost of Parking : {}".format(cost_parking))
print("Cost of total wedding  : {}".format(total_expenses))


lunch_cost=250
cost_breakfast=250/2
noofperson=int(input("enter the no of person:"))
lunch_amount=noofperson*lunch_cost
breakfast_amount=noofperson*cost_breakfast
cost_hall=lunch_amount*1/3
cost_decoration=cost_hall*50/100
cost_parking=cost_hall*10/100
total_expenses=lunch_amount+breakfast_amount+cost_hall+cost_decoration+cost_parking
print("WEDDING EXPENSES")
print("Cost of Hall : {}".format(cost_hall))
print("Cost of Decoration : {}".format(cost_decoration)) 
print("Cost of Lunch : {}".format(lunch_amount))
print("Cost of Breakfast : {}".format(cost_breakfast))
print("Cost of Parking : {}".format(cost_parking))
print("Cost of total wedding  : {}".format(total_expenses)) 
amount_for_groom=total_expenses/2
amount_for_bride=total_expenses/2
print("Expenses for Groom:{}".format(amount_for_groom))
print("Expenses for bride:{}".format(amount_for_bride))
if amount_for_bride>50000:
    print("Bride get a loan")
else:
    print("Bride need not have loan")






    
    
