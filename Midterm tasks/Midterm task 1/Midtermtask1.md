Midterm Lab Task 1

Problem 1. Use Appropriate Escape Sequence( \n, \t \b \ ..etc)
for the problem below

<img width="1076" height="616" alt="image" src="https://github.com/user-attachments/assets/36ef41b0-8eb0-48a6-b989-7ca336cb4fe0" />

Source Code:
     
      print("Database Record\n")
      print("\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\")
      print("Name:\t\tJohn Doe")
      print("Email:\t\tjohn.doe@example.com")
      print("University:\tABC University")

Output:

<img width="517" height="193" alt="image" src="https://github.com/user-attachments/assets/6db15fba-32a8-461d-b21d-ec71b7ec1b38" />



Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f
etc… for this task

<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/938b8d73-0adf-44ed-bf8b-e8bedf73e16d" />


Source Code:
   
    sender = "Jane"
    subject = "Greetings"
    version = 1.2
    discount = 10.50
    status = "A"
    code = "ABCD123"
    location = "City XYZ"
    age = 30
    company = "ABC Corporation"
    website = "www.example.com"
    phone = "+1 123-456-7890"
    job_title = "Software Engineer"
    department = "Engineering"
    
    print("Dear John, I hope this email finds you well.")
    print("I wanted to reach out and say hello.")
    print("I hope you are doing well and enjoying your day.")
    print("It's been a while since we last spoke, and I wanted to catch up with you.")
    print("Let's plan to meet up soon and have a great time together!")
    print(f"Subject: {subject}")
    print(f"Sender: {sender}")
    print(f"Version: {version}")
    print(f"Discount: {discount:.2f}%")
    print(f"Status: {status}")
    print(f"Code: {code}")
    print(f"Location: {location}")
    print(f"Age: {age}")
    print(f"Company: {company}")
    print(f"Website: {website}")
    print(f"Phone: {phone}")
    print(f"Job Title: {job_title}")
    print(f"Department: {department}")


Output:

<img width="759" height="469" alt="image" src="https://github.com/user-attachments/assets/3f867a87-9693-4988-987d-e912ece1f143" />



Problem 3. Book Reservation; Accept User Input

<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/03c18810-af02-4d1d-aa3b-b0d9169f9948" />

Source Code:
   
    title = input("Enter the book title: ")
    author = input("Enter the author: ")
    year = int(input("Enter the year of publication: "))
    genre = input("Enter the genre: ")
    library = input("Enter the library: ")
    member_id = input("Enter your member ID: ")
    return_date = input("Enter the return date: ")
    
    print(f"\nYou have successfully reserved the book '{title}' by {author}.")
    print(f"Year of Publication: {year}")
    print(f"Genre: {genre}")
    print(f"Library: {library}")
    print(f"Member ID: {member_id}")
    print(f"Return Date: {return_date}")

Output:

<img width="757" height="422" alt="image" src="https://github.com/user-attachments/assets/662ec2a8-53ff-4112-9dbb-7aa0795b175a" />


Problem 4. Day Identifier

<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/10e36142-6c97-4fbc-8e53-4670d4b073b9" />


Source Code:
   
    day = int(input("Enter day: "))
    
    if day == 1:
        print("Monday")
    elif day == 2:
        print("Tuesday")
    elif day == 3:
        print("Wednesday")
    elif day == 4:
        print("Thursday")
    elif day == 5:
        print("Friday")
    elif day == 6:
        print("Saturday")
    elif day == 7:
        print("Sunday")
    else:
        print("Invalid input")

Output:

<img width="224" height="179" alt="image" src="https://github.com/user-attachments/assets/21e4cd5a-5b13-47f1-9a74-6f566007f56b" />


