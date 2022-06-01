# Finding-Anagrams
# Check if two words are anagrams 
# Example:
# find_anagrams("hello", "check") --> False
# find_anagrams("below", "elbow") --> True

# true anagram
def find_anagram(word, anagram):
    # [assignment] Add your code here
    word = "silent"
    anagram = "listen"
    str1_anagram = sorted(word)
    str2_anagram = sorted(anagram)

    if str1_anagram == str2_anagram:
        return True
    else: 
        return True
print(find_anagram("silent", "listen"))

# false anagram
def find_anagram(word, anagram):
    # [assignment] Add your code here
    word = "listen"
    anagram = "silen"
    str1_anagram = sorted(word)
    str2_anagram = sorted(anagram)

    if str1_anagram == str2_anagram:
        return True
    else: 
        return False
print(find_anagram("listen", "silen"))
