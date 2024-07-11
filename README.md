# Random-Password-Generator using python
import random
l = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z','A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']
n = ['0','1','2','3','4','5','6','7','8','9']
s = ['!','@','#','$','%','^','&','*','(',')','-','+','_','=','<','.','/','?']
print("Welcome to password Generator!")
n_l=int(input("How many letters you want in your password?\n"))
n_n=int(input("How many letters you want in your password?\n"))
n_s=int(input("How many letters you want in your password?\n"))
password=""
for i in range(1,n_l+1):
    char = random.choice(l)
    password += char
for j in range(1,n_n+1):
    char = random.choice(n)
    password += char
for k in range(1,n_s+1):
    char = random.choice(s)
    password += char
print(password)
