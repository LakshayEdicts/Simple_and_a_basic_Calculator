a = int(input('enter any number'))
b = input('Choose an operator')
c = int(input('enter any number'))
sums = a + c
sub = a - c
product = a * c
divide = a / c

operators = '+', '-', '*', '/', '%'
if b == '+':
    print(sums)
else:
    if b == '-':
        print(sub)
    else:
        if b == '*':
            print(product)
        else:
            if b == '/':
                print(divide)
