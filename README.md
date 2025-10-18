# Student_List
Hi There 👋
this code was created by Mohammad Taha Mohaddessi :

import os

list_student = ["Mohammad", "Taha", "Mohaddessi", "Mohammad Taha Mohaddessi"]

while True:
    index = int(input("\nEnter the student number: "))

    os.system("cls")

    if index >= len(list_student) or index < 0:
        print("We can't find that number in students list!")
    else:
        item = list_student[index]
        print(item)
