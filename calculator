# cs50p final project

def main():
  a = float(input("What's your first number? "))
  b = float(input("What's your second number? "))
  work = int(input("(1=Add | 2=Multiply | 3=Exponent | "
                   "4=Subtraction | 5=Divide)? "))

  if work == 1:
    print("Answer: ", add(a, b))
  if work == 2:
    print("Answer: ", multiply(a, b))
  if work == 3:
    print("Answer: ", exponent(a, b))
  if work == 4:
    print("Answer: ", subtraction(a, b))
  if work == 5:
    print("Answer: ", divide(a, b))

  elif work not in [1, 2, 3, 4, 5]:
    print("You did not select the correct operation. Please try again")

def add(a, b):
  return a + b

def multiply(a, b):
  return a * b

def exponent(a, b):
  return a ** b

def subtraction(a, b):
  return a - b

def divide(a, b):
  return a / b



if __name__ == "__main__":
  main()
