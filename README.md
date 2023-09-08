# Pig_Latin
A special kind of language
#You have two friends who are speaking Pig Latin to each other! Pig Latin is the same words in the same orderexcept that you take the first letter of each word and put it on the end, then you add 'ay' to the end of the word.
#example: (road = 'oadray')

def pig_latin():
    sentence = input("Enter a sentence or word: ").split()
    for word in sentence:
        print(word[1:] + word[:1] + "ay" + " ", end = '')
        
pig_latin()
