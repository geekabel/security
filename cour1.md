

 ## ligne de command linux pour apprentissage perso
 
 :rocket: Commande fréquente
 
```
 cat -n (nom du fichier) : affiche les numero de ligne d'un fichier texte

 wc -l (nom du fichier)  : affiche la somme de ligne d'un fichier

 head -n 20 "fichier" : head est une commande UNIX qui permet d'afficher les premières lignes de texte d'un fichier
```

 
 ####  recherche de fichier dans le fichier .txt

```
 grep "string" filename
 grep "string" /path/to/file
 grep -r "string-name" 
 
 ```
- Avec argument -r  to search for a *string* in your **current directory and all other subdirectories**
      -i ignoring case sensititvity
      -c the total number of lines where the string pattern appears

 
 #### find all the file

   - List all file in directory
       + find .
        
     ```
      find /etc -name "apache2" :   + Searching files using the filename within a specified directory     
     ```
 
