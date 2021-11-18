# Calendar-Project-in-Python


import calendar

year : int(input("Enter the Year: "))

month : int(input("Enter the Month: "))

# calendar.setfirstweekday(calendar.friday) 

fa = calendar.month(month,year)

CA = calendar.calendar(year)

print(fa)

print(CA)
