# progict_python


def check_numbers():
    numbers = []
    n = int(input("Enter number of elements : "))

    for i in range(0,n):
      ele = int(input())
      numbers.append(ele)
    
    for num in numbers:
        if num%2==0:
            print(num, 'is even')
        else:
            print(num, 'is odd')
check_numbers()
