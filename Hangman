print("Welcome to Game:")
word = "ILOVELITTLEPANDA"
print("Total words is: ", len(word))
word_lst = list(word)
guessed_word = len(word)*"_"
guessed_lst = list(guessed_word)
while True:
    my_guess = input("guess_letter: ")

    if guessed_lst == word_lst:
        break

    elif my_guess.upper() in guessed_lst:
        print("Already guessed")

    elif my_guess.upper() in word_lst:
        for index in range(len(word_lst)):
            if word_lst[index] == my_guess.upper():
                guessed_lst[index] = my_guess.upper()
        print("".join(guessed_lst))

print("You won!")
