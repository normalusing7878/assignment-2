# assignment-2
number=int(input('Enter a numer: '))
if number % 2 == 0:
    print(f"({number} is an even number. ")
else:
    print(f"{number} is an odd numeber. ")



total_sum = 0
for i in range(1, 51):
    total_sum += i

print(f"The sum of numbers from 1 to 50 is: {total_sum}")
