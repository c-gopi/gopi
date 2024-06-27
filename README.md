# gopi
#Exception handling is a crucial aspect of programming that allows developers to anticipate and #handle runtime errors or exceptions that may occur during the execution of their code.
# Example 2: Handling File Not Found Error
try:
    with open("nonexistent.txt", "r") as file:
        content = file.read()
    print(content)

except FileNotFoundError:
    print("Error: File not found.")
except Exception as e:
    print("An error occurred:", e)
