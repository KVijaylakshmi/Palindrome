# Palindrome
def check_palindrome(s):
    reversed_s = s[::-1]
    print(f"Reversed: {reversed_s}")
    if s == reversed_s:
        print("The string is a palindrome.")
    else:
        print("The string is not a palindrome.")
input_string = input("Enter a string: ")
check_palindrome(input_string)
