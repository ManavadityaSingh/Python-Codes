# Weight-into-lbs
# Python code for change weight in kg and lbs

weight = int(input('weight: '))
unit = input('(L)bs or (K)g: ')
if unit.upper() == "L":
    converted = weight * 0.45
    print(f"You are {converted} kilos")
else:
    converted = weight / 0.45
    print(f"you are {converted} pounds ")
