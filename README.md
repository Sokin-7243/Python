# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
b) Print your name by using for loop

c) check the user name is palindrome or not
Ans a)
def print_letter_S():
    print("  ***  ")
    print(" *     ")
    print(" *     ")
    print("  ***  ")
    print("     * ")
    print("     * ")
    print("  ***  ")

print_letter_S()

Ans b)
name = "shokin"

for letter in name:
    print(letter)
    Ans c) 
    def is_palindrome(word):
    word = word.lower()
    reversed_word = word[::-1]
    if word == reversed_word:
        return True
    else:
        return False
username = input("Enter the username: ")
if is_palindrome(username):
    print("The username '{}' is a palindrome.".format(username))
else:
    print("The username '{}' is not a palindrome.".format(username))
