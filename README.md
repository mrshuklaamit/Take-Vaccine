# Take-Vaccine
# To take vaccines
Name=input('Enter Name: ')
age=int(input('Enter Your Age: '))
fvaccine=str(input('First Vaccine(Yes/No): '))
svaccine=str(input('Second Vaccine(Yes/No): '))
days=int(input('Days Diff. in First & second Vaccine:' ))
if age >= 18 and age <= 45:
    if fvaccine.lower()=='yes':
      print('Please go for second vaccine with 84 days gap')
    else:
      print('Go for First Vaccine')

elif age > 45 and days >= 84:
    print ('Go for Second Vaccine')

elif svaccine.lower() == 'yes' and days >= 84:
    print('Go for Second Vaccine')
elif age < 18:
    print ('Wait for the Next Announcement')
