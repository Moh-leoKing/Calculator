# Calculator
This is a calculator created by the Python programming language.

[YouTube](https://www.youtube.com/@Moh-leoKing)

![Calculator](https://github.com/Moh-leoKing/Calculator/blob/ee3b5d79b0d144502fba1de84e75b4bbb8c0dc97/repository-open-graph-template.png)

## Start
```
$ python main.py
```

This is the code:

```Python
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error: Cannot divide by zero!"
    return x / y

def main():
    print("Welcome to the Calculator!")
    print("Options:")
    print("1: Add")
    print("2: Subtract")
    print("3: Multiply")
    print("4: Divide")
    
    choice = input("Choose an operation (1/2/3/4): ")
    
    if choice in ['1', '2', '3', '4']:
        num1 = float(input("Enter the first number: "))
        num2 = float(input("Enter the second number: "))
        
        if choice == '1':
            print(f"Result: {add(num1, num2)}")
        elif choice == '2':
            print(f"Result: {subtract(num1, num2)}")
        elif choice == '3':
            print(f"Result: {multiply(num1, num2)}")
        elif choice == '4':
            print(f"Result: {divide(num1, num2)}")
    else:
        print("Invalid choice!")

if __name__ == "__main__":
    main()
```

## Guides
- Python: [Python Docs](https://docs.python.org/3/) - There are many other guides displayed at the top of the page.
