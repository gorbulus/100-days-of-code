# 100 Days Of Code - Log

## Day 0: February 3, 2019

**Today's Progress**: Completed HW 4 for COP2034C Programming in Python.

**Thoughts:** My professor asks us to hardcode string literals as constants, so this was a new way of structuring for me.  I figured out how to format one decimal place, and that you could include the ```{ }``` in your string literal and the ```.format()``` method would work.  

### Here is an  example:

```
# Price, discount rate
purchase_price = 199.99
total_discount = .15

# Calculates purchase price
purchase_price = purchase_price - (purchase_price * total_discount)

# Format token within the string literal
CUSTOMER_TOTAL = "Your total purchase price is ${:.1f}"
CUSTOMER_DISCOUNT = "That quantity qualifies for a {}% discount."

# Format method with constant string
print(CUSTOMER_TOTAL.format(purchase_price))
print(CUSTOMER_DISCOUNT.format(round(total_discount * 100), 2))
```

**Link to work:** [HW4](https://repl.it/@gorbulus/COP2034CHW4)



## Day 1: February 4, 2019

**Today's Progress**: 
1. Completed Lab 5 for COP2034C Programming in Python.
2. Intro to Data Science by RMOTR.  
3. High-level overview of numpy and pandas libraries.

## COP2034C The instructor had us design a Rock, Paper, Scissors Game that used functions, loops, and control flow (if, elif).  

To make it more interesting I implemented a dictionary data structure.

**Link to work:** [Rock, Paper, Scissors](https://repl.it/@gorbulus/COP2034CLab5)

### DS Intro Lab RMOTR is an online Data Science Bootcamp I have been taking since December 4th, 2018.  

Tonight was the first night in the month dedicated to Data Science so I was very excited.

We covered a high-level overview of the Data Science profession and workflow, and learned about numpy and pandas.

**Link to work:** [DS Lab 1](https://notebooks.rmotr.com/gorbulus/ds-intro_lab/lab)





