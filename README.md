# FizzBuzz.py
num = 0
while num <= 20:
    num += 1
    if num%3 == 0 and not num%5 == 0:
        print("fizz")
        
    elif num%5 == 0 and not num%3 == 0:
        print("buzz")
        
    elif num%3 == 0 and num%5 == 0:
        print("fizzbuzz") 
        
    else:
        print(num)
