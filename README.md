# Assignment3
                         # PYTHON BASIC EXERCISES 
# 1. Simple Message
message:str="sir g thora sa makhan lga lun?"
print(message.title())
 #2. Simple MEssage
textsms:str="sir ap buhat acha parhatay hain"
print(textsms.title())
textsms:str="sir g ab tu full number bantay!"
print(textsms.title())
# 3. Personal Message
name:str='Khurram'
print(f'Hello {name} would you like to learn python today?')
# 4. Name Cases
y:str='Khurram'
print(y.lower())
print(y.upper())
print(y.title())
# Famous Quote
quote:str='"Courage is what all matters."'
name:str="QUAID E AZAM"
print(f"{name} said that, {quote}".title())
# Famous Quote 2
famous_person:str='QUAID E AZAM'
message:str="is a hardworking person."
print(f"{famous_person} {message}".title())
# 7. Stripping Names
name = 'Khurram Shahzad'
print("Original Name for white space")
print(f"{name}")
print("         \nname after lstrip():")
print(f"{name}".lstrip())
print("name after rstrip():        ")
print(f"{name}".rstrip())
print("      \nname after strip():      ")
print(f"{name}".strip())
# 8. Variables Sum
x:int
y:int
z:int
x,y,z = 11, 19, 22
print(x+y+z)
# 9. Variables Swap
a=19
b=13
print("Before swap:")
print("a =",a)
print("b ",b)
a, b = b, a
print("After swap:")
print("a =",a)
print("b =",b)
# 10. Favourite colour
favourite_colour='Black'
print(f"My favourite colour is {favourite_colour}")
new_colour='Black'
print(f"My T shirt colour is {new_colour}")
# 11. Changing Pet Name
Pet_name='dog'
Pet_name='cat'
print(f"the new pet name is {Pet_name}")
# 12. Observing Name Error
#- Assign the value "Sunshine" to a variable and print it. Then mistakenly try to print a variable with a different name (like sunshine) and observe the error.
sunshine:str='Sunshine'
# print(sunshine)-->ERROR(NAME NOT DEFINED)
# 13. Reassinging Score
score=96
print(f"My old score is {score}")
score=100
print(f"My new score is {score}")
# 14. City name 
city="Lahore"
print(f"I live in {city}")
# 15. Title Case text
text=" python programming"
print(f"{text}.".title())
# 16. Lower case Conversion
mixedcase='PYthoN PRogramMING'
print(f"{mixedcase}".lower())
# 17 Upper Case Conversion
mixedcase='pyTHOn proGraming'
print(f"{mixedcase}".upper())
# 18. Current Temperature
temperature='35'
print(f"the highest temperature is {temperature} degree")
# 19.Printing a Poem
poem='''Beneath the sky so vast and blue,  
The world awakens fresh and new.  
Each dawn brings light, each dusk brings peace,  
In nature's rhythm, troubles cease.'''
print(poem)
<img width="682" alt="output of assingment3" src="https://github.com/user-attachments/assets/c2769ac1-4e14-4798-95cc-4dc2d32de886">
