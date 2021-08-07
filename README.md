# book-cipher
passage = "You forget what you want to remember and you remember what you want to forget."

numbers = [6, 2, 3, 12, 13, 9]
words = passage.split(" ")
sentence = ""
for i in range(len(numbers)):
    number = numbers[i]
    word = words[number]
    sentence = sentence + word + " " 
print(sentence)
