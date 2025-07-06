# Len-s-Slice
Code academy project to show basic understand of list functions




#original toppings list
toppings = ['pepperoni', 'pineapple', 'cheese', 'sausage', 'olives', 'anchovies', 'mushrooms']
#prices list
prices = [2, 6, 1, 3, 2, 7, 2]
#occurences of 2
num_two_dollars = prices.count(2)
print(num_two_dollars)
#length of toppings list
num_pizzas = len(toppings)
#Advert string
print('We sell', num_pizzas, 'different kinds of pizza!')
#combined list for toppings and prices
pizza_and_prices = [[2, 'pepperoni'], [6, 'pineapple'], [1, 'cheese'], [3, 'sausage'], [2, 'olives'], [7, 'anchovies'], [2, 'mushrooms']]
print(pizza_and_prices)
#add new topping
pizza_and_prices.append([2.5, 'peppers'])
#sorted pizza and price list
pizza_and_prices.sort()
#first variable
cheapest_pizza = pizza_and_prices[0]
#last variable
priciest_pizza = pizza_and_prices[-1]
#remove last variable
pizza_and_prices.pop()
#3 cheapest
three_cheapest = pizza_and_prices[:3]
print(three_cheapest)

#entire list printed with all edits
print(pizza_and_prices)
