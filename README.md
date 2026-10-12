# Python
New to coding
str_input=input("Enter a String:")

upper=0
lower=0
digit=0
special=0
for ch in str_input:
    if ch.isupper() :
        upper+=1
    elif ch.islower():
        lower+=1 
    elif ch.isdigit():
        digit+=1
    else:
        special+=1
        
        
       
print ("Upper Case Count:",upper)
print ("Lower Case Count:",lower)
print ("Digit  Count:",digit)
print ("Special character  Count:",special)
