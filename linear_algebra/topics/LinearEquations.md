# Linear Equations

## Motivation
Suppose you have been tasked with buying three items from the grocery store: milk, eggs, and coffee. You are unsure about the quantity of each item you should buy. However, you know that you have a budget of $30, and eggs cost $2, coffee costs $8, and milk costs $5.

If we allow $x$ to represent the quantity of milk, $y$ to represent the quantity of eggs, and $z$ to represent the quantity of coffee, then the quantity of each item we should buy to stay within our budget can be modeled by the equation:

$50 = 5x + 2y + 8z$

Next, suppose we will be walking home with these items, and as such, must carry them with our hands. Therefore, we can only hold a maximum of 20 pounds of items. Additionally, we know that milk weighs 8 pounds, eggs weigh 1.5 pounds, and coffee weighs 0.5 pounds.

Given this additional information, we can increase the complexity of our model to include the constraints of the weights of each item:

$50 = 5x + 2y + 8z$<br>
$20 = 8x + 1.5y + 0.5z$

Finally, our basket has a finite volume, so our items can only take up so much space.

Milk will take up 1,000 cm³, eggs will take up 500 cm³, and coffee will take up 200 cm³. Our basket can hold a maximum of 5,000 cm³.

Adding this final piece to our equation, we are left with the system:

$50 = 5x + 2y + 8z$<br>
$20 = 8x + 1.5y + 0.5z$<br>
$5000 = 1000x + 500y + 200z$

The end result is what is known as a system of linear equations that when solved will produce us with a solution for x, y, and z that will exactly cost $50, take up exactly 20 pounds, and cover exactly 5000 cm³.
