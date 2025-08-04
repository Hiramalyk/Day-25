# Day-25
tasks = []

while True:
    print("\n1. Add  2. View  3. Remove  4. Exit")
    choice = input("Choose: ")
    
    if choice == "1":
        tasks.append(input("Enter task: "))
    elif choice == "2":
        for i, t in enumerate(tasks): print(f"{i+1}. {t}")
    elif choice == "3":
        tasks.pop(int(input("Task number: ")) - 1)
    elif choice == "4":
        break
