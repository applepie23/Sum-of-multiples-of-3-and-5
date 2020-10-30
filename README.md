# Sum-of-multiples-of-3-and-5
With a user input, find the sum of all the numbers below the user input that are either multiples of 3 or 5. 

number = int(input("Enter a number: "))
place = 1
all_numbers = []
sum = 0

while place < number:
    if place % 3 == 0 or place % 5 == 0:
        all_numbers.append(int(place))
    place += 1
        
for num in all_numbers:
    sum += num

print (sum)
