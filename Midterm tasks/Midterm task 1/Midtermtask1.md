Midterm Lab Task 1


Problem 1. Use Appropriate Escape Sequence( \n, \t, \b \ ..etc) for the problem below


<img width="1076" height="616" alt="image" src="https://github.com/user-attachments/assets/e97e029b-e2b8-4517-ae19-834cc9109557" />


Source Code:



    name = "John Doe"
    ‎email = "john.doe@example.com"
    ‎university = "ABC University"
    ‎
    ‎print("Database Record")
    ‎print("\\\\\\\\\\\\\\\\\\\\")
    ‎print(f"Name:\t\t{name}")
    ‎print(f"Email:\t\t{email}")
    ‎print(f"University:\t{university}")
    

Output:


<img width="974" height="623" alt="image" src="https://github.com/user-attachments/assets/479903e9-c4e3-4f43-9d1d-315e734ab28e" />




Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f etc… for this task


<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/542d1b74-c537-42b4-b298-ca9e2e63adb9" />



Source Code:


    subject = "Greetings!"
    ‎sender = "Jane"
    ‎version = 1.2
    ‎discount = 10.5
    ‎status = "A"
    ‎code = "ABC123"
    ‎location = "City XYZ"
    ‎age = 30
    ‎company = "ABC Corporation"
    ‎website = "www.example.com"
    ‎phone = "+1 123-456-7890"
    ‎job_title = "Software Engineer"
    ‎department = "Engineering"
    ‎
    ‎print(f"Dear John, I hope this email finds you well.")
    ‎print(f"I wanted to reach out and say hello.")
    ‎print(f"I hope you are doing well and enjoying your day.")
    ‎print(f"It's been a while since we last spoke, and I wanted to catch up with you.")
    ‎print(f"Let's plan to meet up soon and have a great time together!\n")
    ‎
    ‎print(f"Subject: %s" % subject)
    ‎print(f"Version: %.2f" % version)
    ‎print(f"Discount: %2f%%" % discount)
    ‎print(f"Status: %s" % status)
    ‎print(f"Code: %s" % code)
    ‎print(f"Location: %s" % location)
    ‎print(f"Age: %d" % age)
    ‎print(f"Company: %s" % company)
    ‎print(f"Website: %s" % website)
    ‎print(f"Phone: %s" % phone)
    ‎print(f"Job Title: %s" % job_title)
    ‎print(f"Department: %s" % department)



Output:


<img width="932" height="688" alt="image" src="https://github.com/user-attachments/assets/bdf096be-c4e8-4326-b4d4-93c7fcc1294d" />


Problem 3. Book Reservation; Accept User Input



<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/feb403f4-ca9c-4588-9a8e-0f5335eaf28d" />



Souce Code:


    title = input("Enter the book title: ")
    ‎author = input("Enter the author: ")
    ‎year = int(input("Enter the year of publication: "))
    ‎genre = input("Enter the genre: ")
    ‎library = input("Enter the library: ")
    ‎member_id = input("Enter your member ID: ")
    ‎return_date = input("Enter the return date: ")
    ‎
    ‎print(f"\nYou have successfully reserved the book '{title}' by {author}.")
    ‎print(f"Year of Publication: {year}")
    ‎print(f"Genre: {genre}")
    ‎print(f"Library: {library}")
    ‎print(f"Member ID: {member_id}")
    ‎print(f"Return Date: {return_date}")


Problem 4. Day Identifier


<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/3cc82ff6-1810-40c3-8002-cb81e9798e1f" />


Source Code:


    day = int(input("Enter day (1-7): "))
    ‎
    ‎if day == 1:
    ‎    print("Monday")
    ‎elif day == 2:
    ‎    print("Tuesday")
    ‎elif day == 3:
    ‎    print("Wednesday")
    ‎elif day == 4:
    ‎    print("Thursday")
    ‎elif day == 5:
    ‎    print("Friday")
    ‎elif day == 6:
    ‎    print("Saturday")
    ‎elif day == 7:
    ‎    print("Sunday")
    ‎else:
    ‎    print("Invalid input")
    
    
Output:



<img width="763" height="349" alt="image" src="https://github.com/user-attachments/assets/a7d4ab8e-fd52-46f7-94c0-21577c44b881" />
‎

