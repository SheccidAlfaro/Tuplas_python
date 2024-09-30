# Tuplas_python
Manejo de tuplas

#Creartupla
thistuple=("manzana, cereza, platano")
print(thistuple)

#Tuplas con miembros duplicados
thistuple2=("manzana, platano, cereza, manzana, cereza")
print(thistuple2)

#Contando miembros de la tupla
thistuple3=("manzana, platano, cereza")
print(len(thistuple3))

#Diferencia cuando es Tupla y cuando NO es 
thistuple4=("Manzana,")
print(type(thistuple4))

#No es tupla
thistuple5=("ajo,")
print(type(thistuple5))

#Asignando tuplas a variables
tuple1=("manzana, platano, cereza")
tuple2=(1, 5, 7, 9, 3)
tuple3=(True, False, False)

#Combinando tipos de datos en mis tuplas
tuplea1=("abc", 34, True, 40, "male")
print(tuplea1)

#Tipo de datos de una tupla
mytuple = ("apple", "banana", "cherry")
print(type(mytuple))


#Utilizando el método tuple para hacer una 
thistuple = tuple(("apple", "banana", "cherry"))
print(thistuple)
![image](https://github.com/user-attachments/assets/e0fbbdc1-ae94-4235-822a-a93e85001083)
![image](https://github.com/user-attachments/assets/855012c2-1c71-4484-aff5-3ac16d1af605)
![image](https://github.com/user-attachments/assets/012f0671-7415-4f0b-9f64-a14f7002fed2)
# listas
#Practica 8  donde usamos listas
thislist = ["apple", "banana", "cherry"]
print(thislist)


#cuando usamos (len( )) te despliega
#el numero de elementos de la lista
thislist2 = ["apple", "banana", "cherry"]
print(len(thislist))


#Separa con un espacio
print(" ")
#Da valores a varias listas
list1 = ["apple", "banana", "cherry"]
list2 = [1, 5, 7, 9, 3]
list3 = [True, False, False]
list4 = ["abc", 34, True, 40, "male"]


#Muestra los miembros de cada lista
print(list1)
print(list2)
print(list3)
print(list4)
print(" ")
thislist = ["apple", "banana", "cherry"]


#Muestra el miembro 1 y comienza en Cero 0
print(thislist[1])

#Muestra el ultimo miembro de la lisa
print(thislist[-1])

#el 2:5 muestra a patir de la posicion 2 a la 5 de los miembros de la lista
#entendiendo que la posicion que tiene apple es 0 cero
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:5])


#Agregando miembros
thislist = ["apple", "banana", "cherry"]
thislist.append("orange")
print(thislist)


#Agregando en la segunda posicion
thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)




#Quitando banana de la lista
thislist = ["apple", "banana", "cherry"]
thislist.remove("banana")
print(thislist)

#Quitando una de las dos bananas de la lista
thislist = ["apple", "banana", "cherry", "banana", "kiwi"]
thislist.remove("banana")
print(thislist)

#borrando al segundo miembro
thislist = ["apple", "banana", "cherry"]
thislist.pop(1)
print(thislist)

#Borrando al ultimo miembro
thislist = ["apple", "banana", "cherry"]
thislist.pop()
print(thislist)

#Borrando al primer miembro
thislist = ["apple", "banana", "cherry"]
del thislist[0]
print(thislist)

#Agregando en la segunda posicion un miembro
thislist = ["apple", "banana", "cherry"]
thislist.insert(1, "orange")
print(thislist)

#Agregando elementos de tropical a la lista
thislist = ["apple", "banana", "cherry"]
tropical = ["mango", "pineapple", "papaya"]
thislist.extend(tropical)
print(thislist)


#Agregando Tuplas a lista
thislist = ["apple", "banana", "cherry"]
thistuple = ("kiwi", "orange")
thislist.extend(thistuple)
print(thislist)
![image](https://github.com/user-attachments/assets/41355c41-8e5f-4f70-8210-003798875ecf)
![image](https://github.com/user-attachments/assets/2b8543c8-f392-4616-b5b3-7d3fc632ddac)
![image](https://github.com/user-attachments/assets/2d5cff52-e875-4548-9fa2-341a0569539f)

![image](https://github.com/user-attachments/assets/2f4d7d09-a00a-4806-ac83-89fb87691ab0)





