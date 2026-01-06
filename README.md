# float-program
d = int(input("Enter Number of days: "))
fine = 0

if d <= 5:
    fine = d * 0.50
    print("Fine :", float(fine))

elif d <= 10:
    i = d - 5
    fine = (5 * 0.5) + (i * 1)
    print("Fine :", float(fine))

elif d <= 30:
    i = d - 10
    fine = (5 * 0.5) + (5 * 1) + (i * 5)
    print("Fine :", float(fine))

else:   
    extra = d - 30
    fine = (5 * 0.5) + (5 * 1) + (20 * 5) + (extra * 5)  # full calculation
    print("Your Membership is cancelled")
    print("Fine amount (Rs):", float(fine))
OUTPUT:
Enter Number of days: 14
Fine : 27.5

