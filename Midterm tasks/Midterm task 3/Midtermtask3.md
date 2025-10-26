Midterm Lab Task 3:

Modify the menuCart program and include the following requirements:

Problem 1: Validate user choice (If choice is not in the cart) - "display item is not in the cart"

Problem 2: Input Customer Name and Age if age is 60 and above provide 20% discount from the total purchased.



Source Code:


    menu = {'Burden': 35.00,
            'Tacos': 50.00,
            'Fries': 20.00,
            'Iced Coffee': 25.00}
    
    cart = []
    total = 0
    
    print("--------- M E N U ---------")
    for key, value in menu.items():
        print(f"{key:12}: ₱{value:0.2f}")
    print("----------------------------")
    
    # accept user choice/input
    while True:
        food = input("Select an item from the menu (q to quit): ")
        if food.lower() == 'q':
            break
        elif food not in menu:
            print("Item is not in the menu, please choose again.")
        else:
            cart.append(food)
    
    # display user input
    print("\nYour Orders are....")
    for food in cart:
        total += menu.get(food)
        print(food, end=", ")
    
    print(f"\nTotal Purchased: ₱{total:0.2f}")
    
    # Customer details
    name = input("\nEnter Customer Name: ")
    age = int(input("Enter Customer Age: "))
    
    # discount if 60+
    if age >= 60:
        discount = total * 0.20
        total -= discount
        print(f"Senior Discount Applied (20%): -₱{discount:0.2f}")
    
    print(f"\nCustomer: {name}")
    print(f"Final
    
    print(f"\nCustomer: {name}")
    print(f"Final Total: ₱{total:0.2f}"): ₱{total:0.2f}")


Output 1 and 2:



<img width="480" height="722" alt="image" src="https://github.com/user-attachments/assets/f187a61a-b74e-4bce-89a3-4bcf32fb77c6" />

    
