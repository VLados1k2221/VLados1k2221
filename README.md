a = int(input("zadajte první čislo"))
b = int(input("zadajte druhe čislo"))

soucet = a + b 
rozdil = a - b 
soucin = a * b 
podil = a / b 

print(soucet)
print(soucin)
print(rozdil)
if a == 0:
    print("Nelze dělit 0")
else:
    print(podil)
