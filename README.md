# Fahrenheit-Celsius-Calculator-
#step 1:
#first youll have to figure out how you will exclude the letter 
#so that we can makke the str an int 
#youll have to find a loop like if char(len(str)) is F the use formulate else c

#step1
#getting the order of the last letter o the str then make an if state ment 
temp_input =input()
temp_unit = ord(temp_input[len(temp_input)-1])

#Step 1.1
#before you take the calculation you need to define the int and outside the condition
temp_digits = float(temp_input[0:len(temp_input)-1])

#make an if\else statement that will make it so the correct formulate is used

#calculation for celcius
if temp_unit ==70: 
   temp_conv = (temp_digits *9/5)+32
   print(temp_conv,"C")   #within the str youll have to creat a way to concatinate it with the correct unit
   
   #calculation for F
elsif temp_unit ==67:
  temp_conv = (temp_digits -32)*5/9
  print(temp_conv,"F")

#Step 2:
#youll have to convert the int and do a calaculations 
