# a function that takes a string and returns a string with its letters in alphabetical order
User input 
string conversion to characters
Sort function to arrange the letters in ascending order
for i in word:
    print(i, end= "") Don't move to a new line

#Unpacking List 

lst = [1, 2, 3, 4, 5, 6] #store variables inside the word lst
first = lst[0] #1st index is stored in the first variable
middle = lst[1:5] #slicing index 1 to 5 but the 5th index is not included
last = lst[5] #5th index is stored in the last variable

print("first:", first) #Print first 
print("middle:", middle) #print middle
print("last:", last) #print last 

#a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon

def emotify(): #define function emotify
    return ( #return function
        input("Input a Sentence: ") #user input
        .replace("Smile", ":)") #replace function for desired emoticon when entered the trigger word
        .replace("Grin", ":D") #replace function for desired emoticon when entered the trigger word
        .replace("Sad", ":(") #replace function for desired emoticon when entered the trigger word
        .replace("Mad", ">:(") #replace function for desired emoticon when entered the trigger word
    )

print(emotify()) #run the function
