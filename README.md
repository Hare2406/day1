# day1
# input a number 
# output weird and not weird 
#  conditions weird when it is odd and even (between 6 to 20 )
# conditon not weird when if is even (b/w 2 to 5) (greater then 20 )
# find even or odd number 
# then check the number are in between and the print 
n = int(input(""))

if n % 2 != 0:
    print("Weird")
elif 2 <= n <= 5:
    print("Not Weird")
elif 6 <= n <= 20:
    print("Weird")
else:  # n > 20 and even
    print("Not Weird")
