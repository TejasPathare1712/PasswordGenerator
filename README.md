# PasswordGenerator
import random
password = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz1234567890!@#$%"
length_password = int(input("Enter the length of password"))
a = "".join(random.sample(password,length_password))
print(f"Your Password is {a}")

