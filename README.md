# assignment-4

#to create and display letters
import itertools      
d ={'1':['a','b'], '2':['c','d']}
for combo in itertools.product(*[d[k] for k in sorted(d.keys())]):
    print(''.join(combo))
Output-ac
       ad
       bc
       bd


# create dictionary from string
str1 = 'w3resource' 
my_dict = {}
for letter in str1:
    my_dict[letter] = my_dict.get(letter, 0) + 1
print(my_dict)
Output-{'w': 1, '3': 1, 'r': 2, 'e': 2, 's': 1, 'o': 1, 'u': 1, 'c': 1}

# convert tuple to string
tup = ('s', 'i', 'n', 'd', 'h', 'u') 
str =  ''.join(tup)
print(str)
Output-sindhu


# to slice a tuple
my_tuple = ('a', 'b', 'c', 'd')
print(my_tuple[1:]) 
print(my_tuple[:2]) 
print(my_tuple[1:3]) 
print(my_tuple[::2])
Output-('b', 'c', 'd')
       ('a', 'b')
       ('b', 'c')
       ('a', 'c')

#create a tuple
tuplex = tuple("gitam university")
print(len(tuplex))
Output-16
