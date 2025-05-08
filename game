import random

def guess_the_number():
    print("Sveiki! Es izdomāju skaitli no 1 līdz 100. Mēģini uzminēt!")

    number_to_guess = random.randint(1, 100)
    attempts = 0

    while True:
        try:
            guess = int(input("Tavs minējums: "))
            attempts += 1

            if guess < number_to_guess:
                print("Skaitlis ir par mazu.")
            elif guess > number_to_guess:
                print("Skaitlis ir par lielu.")
            else:
                print(f"Apsveicu! Tu uzminēji skaitli {number_to_guess} ar {attempts} mēģinājumiem.")
                break
        except ValueError:
            print("Lūdzu, ievadi veselu skaitli.")

# Spēles palaišana
guess_the_number()
