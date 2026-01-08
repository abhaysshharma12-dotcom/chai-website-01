# Tea Stall Ordering System

# Menu dictionary: item -> price
menu = {
    "tea": 2.50,
    "coffee": 3.00,
    "sandwich": 5.00,
    "cake": 4.00,
    "exit": 0  # Special item to finish ordering
}

def display_menu():
    print("\n--- Tea Stall Menu ---")
    for item, price in menu.items():
        if item != "exit":
            print(f"{item.capitalize()}: ${price:.2f}")
    print("Type 'exit' to finish ordering.\n")

def main():
    order = {}
    total = 0.0
    
    print("Welcome to the Tea Stall!")
    
    while True:
        display_menu()
        item = input("What would you like to order? ").lower().strip()
        
        if item == "exit":
            break
        elif item in menu:
            quantity = int(input(f"How many {item}s? "))
            if quantity > 0:
                order[item] = order.get(item, 0) + quantity
                print(f"Added {quantity} {item}(s) to your order.")
            else:
                print("Invalid quantity.")
        else:
            print("Sorry, that's not on the menu.")
    
    # Calculate totals
    print("\n--- Your Order ---")
    for item, qty in order.items():
        price = menu[item]
        item_total = qty * price
        total += item_total
        print(f"{item.capitalize()} x{qty}: ${item_total:.2f}")
    
    tax = total * 0.10  # 10% tax
    grand_total = total + tax
    
    print(f"\nSubtotal: ${total:.2f}")
    print(f"Tax (10%): ${tax:.2f}")
    print(f"Total: ${grand_total:.2f}")
    
    # Payment
    payment = float(input("\nEnter payment amount: $"))
    if payment >= grand_total:
        change = payment - grand_total
        print(f"Payment successful! Change: ${change:.2f}")
    else:
        print("Insufficient payment. Order canceled.")
    
    print("Thank you for visiting the Tea Stall!")

if __name__ == "__main__":
    main()