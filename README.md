# Day-3-week-2-assignment-
Assignment for week 2 day 3
Create a function named calculate_discount(price, discount_percent) that calculates the final price after applying a discount. The function should take the original price (price) and the discount percentage (discount_percent) as parameters. If the discount is 20% or higher, apply the discount; otherwise, return the original price.

def calculate_discount(price, discount_percent):
    """
    Calculate the final price after applying a discount if the discount is 20% or higher.
    
    Parameters:
    price (float): The original price of the item.
    discount_percent (float): The discount percentage to be applied.
    
    Returns:
    float: The final price after applying the discount, or the original price if no discount is applied.
    """
    if discount_percent >= 20:
        return price - (price * (discount_percent / 100))
    else:
        return price
        
Using the calculate_discount function, prompt the user to enter the original price of an item and the discount percentage. Print the final price after applying the discount, or if no discount was applied, print the original price
