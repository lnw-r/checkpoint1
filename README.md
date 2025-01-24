# checkpoint1
evaluation
# Exercice 1
![Capture d’écran EXERCICE 1 CHEKPOINT](https://github.com/user-attachments/assets/a95f94dd-c652-4930-b2f3-ef821a3df9a3)
# Exercice 3

1. cat /ect/passwd
2.chmod 744 myfile
3. la différence entre  une variable d'environement et une variable local est que la variable d'environement  est accecible par tout les processus enfantsqui sont définie avec export alors que la variable locale elle est eccecible uniquement dans le script ou la fonction où elle est définie sans export.
4.  la structure if en bash permet d'exécuter des commande ssi une conditions est vrai
   exemple:
#!/bin/bash
fichier="monfichier.txt"
if [ -e "$fichier" ]

then 
echo "le fichier existe"
else 
echo " le  fichiern'existe pas"
fi
