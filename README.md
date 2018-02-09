[![Build Status](https://travis-ci.org/Org-Pro/orgpro-ihm.svg?branch=master)](https://travis-ci.org/Org-Pro/orgpro-ihm)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0eae2a86b03f4b10b9999c40a51ab020)](https://www.codacy.com/app/Trellorg/orgpro-ihm?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Org-Pro/orgpro-ihm&amp;utm_campaign=Badge_Grade)
[![Coverage Status](https://coveralls.io/repos/github/Org-Pro/orgpro-ihm/badge.png?branch=master)](https://coveralls.io/github/Org-Pro/orgpro-ihm?branch=master)


# Guide d'installation

## Pour Linux

### Pré-Requis
Installer JAVA 8  
Les commandes :  
- sudo add-apt-repository ppa:webupd8team/java  
- sudo apt-get update  
- sudo apt-get install oracle-java8-installer  
 
Puis décompresser le projet
    
### Compilation
A partir du répertoire courant du projet :  
Puis :  
- chmod +x gradlew  
- ./gradlew build  
    
### Lancer l'application
A partir du répertoire courant du projet :  
Les commandes : (Remplacer xxx.jar par le nom du fichier)  
- cd build/libs/  
- java -classpath xxx.jar fr.trellorg.api.project.Main
    
## Pour Windows

### Pré-Requis
Installer JAVA 8 (Version 8)  
Via le site : <https://www.java.com/fr/download/>  

Puis décompresser le projet

### Compilation
A partir du répertoire courant du projet :  
Lancer le fichier "build.bat"  

Ou depuis un terminal :  
Les commandes :  
- gradlew.bat build

###  Lancer l'application
A partir du répertoire courant du projet :  
Lancer le fichier "run.bat"  

Ou depuis un terminal :  
Les commandes : (Remplacer xxx.jar par le nom du fichier)  
- cd build/libs/  
- java -classpath xxx.jar fr.trellorg.api.project.Main
