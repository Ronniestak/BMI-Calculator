# BMI Calculator 

name = input('Enter your name: ')

weight = int(input('Please enter your weight in Pounds: '))

height = int(input('Please enter your height in Inches: '))

BMI = (weight * 703) / (height * height)

print('Your BMI Value is: ')

print(BMI)

if BMI > 0:
    if (BMI<18.5):
        print(name + ', you are underweight.')
    elif(BMI<24.9):
        print(name + ', you are normal weight.')
    elif(BMI<29.9):
        print(name + ', you are over weight.')
    elif(BMI<34.9):
        print(name + ', you are obese.')
    elif(BMI<39.9):
        print(name + ', you are severly obese.')
    else:
        print(name + ', you are morbidly obese.')
else:
    print('Please enter valid value')
