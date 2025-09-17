import random
letters = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

number = int(input("Podaj długość hasła: "))
password = ""

for i in range(number):
    letter = random.choice(letters)
    password += letter
    
print(password)
