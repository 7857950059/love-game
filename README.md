# love-game
Here's the Love Game created using the random module in Python along with if-elif-else conditions:



import random

kitna_pyar_kerti_h_ = random.randrange(1, 101)
user_input = int(input("Enter The value:---"))

difference = abs(user_input - kitna_pyar_kerti_h_)

if difference > 20:
    if user_input < kitna_pyar_kerti_h_:
        print("Love Number:", kitna_pyar_kerti_h_)
        print("Bhut jayda pyar hai.")
    elif user_input > kitna_pyar_kerti_h_:
        print("Love Number:", kitna_pyar_kerti_h_)
        print("Bilkul Pyar nhi hai.")
    else:
        print("Love Number:", kitna_pyar_kerti_h_)
        print("50-50H")
else:
    if user_input < kitna_pyar_kerti_h_:
        print("Love Number:", kitna_pyar_kerti_h_)
        print("Pyar Kerta H")
    elif user_input > kitna_pyar_kerti_h_:
        print("Love Number:", kitna_pyar_kerti_h_)
        print("Pyar Nhi Kerta H")
    else:
        print("Love Number:", kitna_pyar_kerti_h_)
        print("50-50H")
