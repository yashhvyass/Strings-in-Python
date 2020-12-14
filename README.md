# Strings-in-Python
#Deleting the strings of k length
'''str = 'the name is yash vyas'
k = int(input())
temp = str.split()
for i in temp:
    if len(i) != k:
        print(i)'''
        
#Python program to print even length words in a string
'''str = 'what is your name isi'
temp = str.split()
for i in temp:
    if len(i) % 2 == 0:
        print(i)
'''        
#Python Program to Return the Length of the Longest Word from the List of Words
'''def longestw(words):
    listf = []
    for word in words:
        listf.append([len(word), word])
    
    listf.sort()
    
    print listf[-1][1] # but how to print when one int and other str

str = ['one', 'two', 'three']
longestw(str)
'''
