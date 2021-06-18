# Basic_ML
python programs¶
1.) Python Program to Display Fibonacci Sequence Using Recursion

In [ ]:
# Python program to display the Fibonacci sequence

def recur_fibo(n):
   if n <= 1:
       return n
   else:
       return(recur_fibo(n-1) + recur_fibo(n-2))

nterms = 10

# check if the number of terms is valid
if nterms <= 0:
   print("Plese enter a positive integer")
else:
   print("Fibonacci sequence:")
   for i in range(nterms):
       print(recur_fibo(i))
2.Python Program to Sort Words in Alphabetic Order

In [ ]:
# Program to sort alphabetically the words form a string provided by the user

my_str = "Hello this Is an Example With cased letters"
words = [word.lower() for word in my_str.split()]

# sort the list
words.sort()

# display the sorted words

print("The sorted words are:")
for word in words:
   print(word)
3.Python Program to Reverse a Number

In [ ]:
num = int(input())
reversed_num = 0

while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digitd
    num //= 10

print("Reversed Number: " + str(reverse_num)
