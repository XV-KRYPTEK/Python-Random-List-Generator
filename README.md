# Python-Random-List-Generator
This program provides a simple list generator in Python. You are able to set how many numbers you want in your list.

Duplication of the code :

#Générateur de listes aléatoires de 13 caractères
import random

# Résultat que l'on va avoir + caractères demandés 
res = [random.randrange(1, 99, 1) for i in range(45)]
 
 #affichage du résultat
print ("Random number list is : " +  str(res))
