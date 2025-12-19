# python-tuple-mean-calculator
tpl = eval(input("Enter Tuple: "))
length = len(tpl)
total = 0

for i in range(length):
    total = total + tpl[i]

mean = total / length

print("Given tuple is:", tpl)
print("The Mean of given tuple is:", mean)


INPUT & OUTPUT:
Given tuple is: (10, 20, 30, 40, 50)
The Mean of given tuple is: 30.0

