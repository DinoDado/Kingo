# Kingo
2 little projects 

#new zealand problem

start = 10000
spend_lst = [1200, 900, 354, 1300, 550, 620, 550, 715]
total = sum(spend_lst)
print("Total:", total)
money_left = start - total
print("You have", money_left, "dollars")
average = total / len(spend_lst)
print("The average per week:", average)
weeks_left = money_left / average
print("You have approx.", weeks_left, "weeks left to travel")
