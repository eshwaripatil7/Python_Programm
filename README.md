# Python_Programm
print nums based on the user input and repeat it 2 times then get exit.
min_value=int(input("enter minimum value"))
max_value=int(input("enter maximum value"))
num=min_value-max_value
for num in range(min_value,max_value+1):
  print(num)
while True:
  min_value=int(input("enter minimum value"))
  max_value=int(input("enter maximum value"))
  num=min_value-max_value
  for num in range(min_value,max_value+1):
    print(num)
  exit()
