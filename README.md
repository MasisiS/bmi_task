# bmi_task
weight = int(input("Enter your weight in kg:"))
height = int(float(input("Enter your height in m:")))

BMI = (weight) / ((height)*(height))

if BMI >= 30:
 print("the user is obese")

elif BMI >= 25:
 print("the user is overweight")

elif BMI >= 18.5:
 print("the user is normal")

elif BMI < 18.5:
 print("the user is normal")
