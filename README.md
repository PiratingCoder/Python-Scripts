#RETURNS THE SUM OF NUMBER ONE AND NUMBER TWO.
def add(num1, num2):
    return num1 + num2
def sub(num1, num2):
    return num1 - num2
def div(num1, num2):
    return num1 / num2
def mul(num1, num2):
    return num1 * num2

def main():
    operation = input("What would you like to do? +, -, *, or /: ")
    if(operation != '+' and operation != '-' and operation != '*' and operation != '/'):
        #INVALID OPERATION
        print("Please use the correct symbol. + = plus, - = subtract, * = multiply and / = divide.")

    else:
        num1 = int(input("Enter num1: "))
        num2 = int(input("Enter num2: "))
        if(operation == '+'):
            print(add(num1, num2))
        elif(operation == '-'):
            print(sub(num1, num2))
        elif(operation == '*'):
            print(mul(num1, num2))
        else:
            print(div(num1, num2))
        
                

main()
        
