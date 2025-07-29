# Learning-Python
Starter guide to cybersecurity


#hey.....let's fucking go


print ("This is the first of many programs I will write in Python")

print("I am el-papi")
print("Let's fucking go")
print("save the world")

#show them nothing but the best

print("""hello 
No,i am el-papi
No,i am johnny""")

#New line indicator
print("Hello \n" + "boy, \n" + "how are you\n")

#New line multiplier
print("I am el-papi \n" * 100)

#let's play with some numbers

name = "Elpapi"
age = 28
actual_age = 28.68

maths = 10 + 10/2 - 10 * 2

result = age + actual_age + maths

print(result)


#if statements......Comparison operator

#Greet the customer by name and thank them for coming in today.
if name == "Jessica":
  print("you're not welcome here Jessica! Get out!")

else:
  print("Hello " + name + ", thank you for coming in today!\n\n")

#if 2 > 3:
  #print("Yep, its true")
  #print("very true")

#else:
  #print("Nope, not true")
  #print("not very true")


  #Adding more IF & Else statements

  #Greet the customer by name and thank them for coming in today. if customer is Jessica, do not welcome her
name = input("what is your name? ")
if name == "Jessica":
  evil_status = input("Are you evil?\n")
  if evil_status == "Yes":
   print("you're not welcome here Jessica! Get out!")
   exit()
  else:
    print("Hello Jessica, what can I do for you?\n\n")

else:
  print("Hello " + name + ", thank you for coming in today!\n\n")



  #OR & AND STATEMENT
  
if name == "Jessica" or name == "John":
   evil_status = input("Are you evil?\n")
   good_deeds = int(input("How many good deads have you done?\n"))
  if evil_status == "Yes" and good_deeds > 4 :
   print("you're not welcome here " + name+ "! Get out!")
   exit()
  else:
    print("Hello " + name+ ", what can I do for you?\n\n")
  #IF NOT STATEMENT
  
if name != "Jessica":
    print("Sorry Jessica, we do not serve you.")
else:
    print("Hello " + name + ", thank you for coming in today!")



    #Python list
#Let's create a list of fruits

fruits = ["apple", "banana", "cherry", "date", "elderberry", "fig", "grape"]

#Note, we use braclets here to define a list

print(fruits)

#Lets print a list with Integers, Floats and Strings and booleans

camp_list = ["Food", 10 , 20.5, True]

we = camp_list[3]
me = fruits[4]

print (we)
print (me)


#let's learn more about list
#removing from the list

supplies = ["tent", "sleeping bags", "water", "raspberry pi", "coffee", "knife", "ethernet cable", "flash drive", "beard oil", "marshmallows"]

camp_site = ["crystal lake", 404, 89.3, True]

#adding toilet paper to the list


supplies.remove("coffee")

print(supplies.pop(0))

#prints outside of the list

print(supplies)

