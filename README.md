# 258456
x = int(input("Give me a 4 digit number that is even but does not end with 0"))
if x >= 1000 and x <= 9999 and x%2 == 0 and not x%10 == 0:
    print("Good ")
else:
    print("Nope, that's not right! Something is wrong")
quit()
