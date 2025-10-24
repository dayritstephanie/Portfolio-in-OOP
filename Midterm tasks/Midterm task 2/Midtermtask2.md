Midterm Lab Task 2:

<img width="669" height="701" alt="image" src="https://github.com/user-attachments/assets/1761e7e1-4f3a-4e46-bf9c-e111ffd1a952" />

Source Code:

    product_name = str(input("Enter Product Name:"))
    category = str(input("Enter Category:"))
    quality = float(input("Enter Quality Rating:"))  
    price = float(input("Enter Price Rating:"))
    service = float(input("Enter Service Rating:"))  
    
    def calculate_average_rating(quality,price,service):  
      total = quality + price + service  avg = total / 3  return avg  
    
    def analyze_product():  
      print("Product Name: %s " %product_name )
      print("Category: %s" % category )
      print("Quality Rating: %.2f" % quality) 
      print("Price Rating: %.2f "% price)  
      print("Service Rating: %.2f" % service)  
      print("Overall Average Rating: %.2f" % calculate_average_rating(quality, price, service)) 
      
    analyze product()


Output:

Sample Output 1:

<img width="692" height="406" alt="image" src="https://github.com/user-attachments/assets/a4639016-d24d-4131-9a5b-addca32f61d7" />

Sample Output 2:

<img width="561" height="389" alt="image" src="https://github.com/user-attachments/assets/055f5b85-1d1a-4c4a-9289-0ffd3d4b0fbb" />
