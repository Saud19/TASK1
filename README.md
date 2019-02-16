# Task 1.1

Student_Details = []
Index = 0
bool= True

while Index < 3:
     Student_Name = input("Please enter the Students Name: ")
     Email_ID = input("Please enter the students Email ID: ")
     Student_Details += [(Student_Name + "#" + Email_ID)]
     Index += 1
print("Name AND Email ID" "\n")
print(*Student_Details, sep = "\n")

# Task 1.2

def is_empty(Student_Details):
    if Student_Details:
        print('Structure is not empty.')
    else:
        print('Structure is empty.')

# Task 1.3

Search_Value = input("Please enter the Students Name you are searching for: ")
Found = False
if Search_Value in [Student_Details]:
  Found = True
  print(Search_Value).format(Student_Details)
else:
  print("Student Details NOT FOUND")

# Task 1.4

Search_Term= input("Please enter the name of the Student: ")
if Search_Term in Student_Details:
   print(Search_Term)
   print(*Student_Details, sep = "\n")
else:
   print("Name Not Found")


# Task 1.5 & Task 1.6
# r = number of rows
# c = number of columns

Number_of_Students = input("Enter the Number of Students: ")
r=3
c= Number_of_Students

Student_Details={(i,j):0 for i in range(3) for j in range(4)}
Student_Details.append
Student_Name=input("Please enter your name: ")
Email_ID=input("Please enter your Email ID:")
Date_of_Birht=input("Please enter your Date of Birth: ")
Student_ID=input("Please enter your Student ID Number: ")
