# eli


#Lilly's version
]wordle = "hello"
def word_guess(guess):
    new_guess = ['x', 'x', 'x', 'x' 'x']
    guess = input("What is your guess?")
    for i in range(6):
     for letter in wordle:
        if guess[letter] == guess[letter]:
            print(f"The {letter} letter is correct")
            new_guess.replace(new_guess[letter], guess[letter])
        else:
           guess[l] = guess[l]
print(word_guess())


