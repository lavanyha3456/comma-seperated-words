# comma-seperated-words

items = input("Input comma separated sequence of words")
words = [word for word in items.split(",")]
print(",".join(sorted(list(set(words)))))


Output:
Input comma separated sequence of wordsred,white,black,red,green,black

black,green,red,white
