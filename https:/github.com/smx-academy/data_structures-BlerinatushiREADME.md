### Hi there 👋

<!--
**Blerinatushi/Blerinatushi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

l1=[1,2,3,4,5]
l2=[6,7,8,9,10,11]
Dolzhina_l1=len(l1)
Dolzhina_l2=len (l2)
print('Brojot na elementi vo lista 1 e {}, dodeka na lista2 e {}'. format(Dolzhina_l1, Dolzhina_l2))

l1.insert(0,1)
print (l1)
l1_1=l1[ :1]+l1[2:]
print(l1_1)
l3=l1_1+l2
print (l3)
Dolzhina_l3=len(l3)
print(Dolzhina_l3)
l4=sorted (l3, reverse = True)
print (l4)

my_list=[5,10,15,20,25]
vtor_element=my_list[1]
print('Vtoriot element vo my_list e {}'. format (vtor_element))
my_list.append (30)
print (my_list)
my_list.insert (0,0)
print (my_list)

lista_sortirana = sorted (my_list, reverse=True)
print(lista_sortirana)
sub_lista = my_list[1: ]
print(sub_lista)

lista10=[1,2,3,4,5,6,7,8,9,10]
a=int(input ('Vnesi broj:'))
b=int(input ('Vnesi broj:'))

if a<b:
    print('Vnesovte greshka')
if a<0:
    print ('Vnesovte negativen broj')
if b<0:
    print('Vnesovte negativen broj')
if b> len(lista10):
print (' Vnesete pomal broj')
print()

sub_lista10=lista10 [0: ]
print(sub_lista10)

sub_sub_lista10= " ".join(str(sub_lista10))
print (sub_sub_lista10)

Sodrzhi_6= sub_sub_lista10  __contains__(' 6')
print ('Sublistata go sodrzhi elementot {}'. format (Sodrzhi_6))

grade = {'Alice':90, 'Bob':85, 'Charlie':95, 'Dave':80, 'Eve':100}
A=grade ['Alice']
print (A)
grade.update ({'Dave':75})
print (grade)
grade ['Franc']=92
print (grade)

del grade ['Bob']
print (grade)
ucenici=grade.keys()
lista_ucenici=list (grade.keys())
print(lista_ucenici)
lista_ucenici_broj=len (lista_ucenici)
print (lista_ucenici_broj)

poeni=grade.values()
lista_poeni=list (grade.values())
book_dict = {'Mystery': ['The Girl with the Dragon Tattoo', 'Gone Girl', 'The Da Vinci Code'],
    'Romance': ['The Notebook', 'Pride and Prejudice', 'The Fault in Our Stars'],
    'Science Fiction': ['The Hunger Games', 'Ender\'s Game', 'Dune'],
    'Fantasy': ['The Lord of the Rings', 'Harry Potter and the Philosopher\'s Stone', 'A Game of Thrones'],
    'Classics': ['To Kill a Mockingbird', 'The Catcher in the Rye', 'Wuthering Heights']}
print (book_dict)
#
book_dict.update ({'Science Fiction': ['The Hunger Games','Dune']})
print (book_dict)
#
book_dict_zharnovi= book_dict.keys()
lista_zhanrovi= list (book_dict.keys())
print (lista_zhanrovi)

Knigi_fantasy= book_dict['Fantasy']
print (Knigi_fantasy)


Broj_na_knigi=len (Knigi_fantasy)
print (Broj_na_knigi)

Knigi_fantasy= book_dict['Fantasy']
print(Knigi_fantasy)
Sodrzhi=Knigi_fantasy __contains__('The Lord of the Rings')
print ('Dali naslovot {} se sodrzhi vo Fantasy zharnot'. format (Sodrzhi))
