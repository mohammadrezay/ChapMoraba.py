# ChapMoraba.py
https://quera.org/problemset/591?tab=description
def square(n):
    print(n * '*')
    for i in range(n-2):
        print('*'+' '*(n-2) + '*')
    print(n * '*')   
square(int(input()))
