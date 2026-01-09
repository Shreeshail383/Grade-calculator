marks = int(input("Enter your marks: "))

if marks>90:
    print("You secured a grade 'A' ")
elif marks>=75 and marks<=90:
    print("You secured a grade 'B' ")
elif marks>=50 and marks<=74:
    print("You secured a grade 'C' ")
else:
    print("Yor are failed!")
