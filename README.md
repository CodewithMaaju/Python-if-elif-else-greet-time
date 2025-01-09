#we are going to do excerise using if, else and elif statment 
#Exercise will be like according to the time of the day our code show will greet. 
#so lets get started
a = int(input("Enter your time: "))
print('your time is ', (a))
if(a<12):
  print("Good Morning sir")
  print("Can you take your breakfast")
  print("We have multiple option")
  print("Healthy punjabi food to Western modern food")
elif(a<=15):
  if(a<=15):
    print("Good Afternoon Sir")
    print("Can you take your Luch")
    print("We have multiple option")
    print("Healthy punjabi food to Western modern food")
  elif(a<=18):
    print("Good Evening Sir")
    print("Would you like to have a dinner")
    print("We have multiple options")
  else:
    print("Good Night Sir")
    print("we are closed")
else:
  print("We are Closed")
  print("Visit us tomorrow")
print("Thank you for visiting our restraunt")
print("Enjoy your meal")
