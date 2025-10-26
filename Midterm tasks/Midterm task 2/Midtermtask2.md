Midterm Lab Task 2:



<img width="669" height="701" alt="image" src="https://github.com/user-attachments/assets/e08e5004-1db3-41fd-a2e7-d66f632ecc11" />



Source Code:


    def Calcu_Avg_Rates(quality, price, service):
        """This function calculates the average of three ratings."""
        return (quality + price + service) / 3
    
    
    def Ana_Prod_Rates(brandname, category, quality, price, service):
        """This function displays product details and calls the Calcu_Avg_Rates function."""
        print("\nBrand Name:", brandname)
        print("Category:", category)
        print("Quality Rating:", f"{quality:.2f}")
        print("Price Rating:", f"{price:.2f}")
        print("Service Rating:", f"{service:.2f}")
        
        avg = Calcu_Avg_Rates(quality, price, service)
        print("Overall Average Rating:", f"{avg:.2f}")
    
    
    # Main Program
    brandname = input("Enter Brand Name: ")
    category = input("Enter Category: ")
    quality = float(input("Enter Quality Rating: "))
    price = float(input("Enter Price Rating: "))
    service = float(input("Enter Service Rating: "))
    
    Ana_Prod_Rates(brandname, category, quality, price, service)



Output 1:




<img width="720" height="255" alt="image" src="https://github.com/user-attachments/assets/c6668823-6540-4e82-9cc7-ddc5d26dff31" />


