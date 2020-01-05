# **1ER DAM. Desarrotllament D'Aplicacions Multiplataforma. EDD. Entorns de Desenvolupament.**

***2019-Editat per Máxim Sánchez Porta***


# Index:



>### UNITAT 4. Automatització amb Make.
>
>***[1.-Com instalar Git i Make en Ubuntu 18.](https://github.com/Maxim1erDAM/EDD/blob/master/Unitat%202/Unitat2.md#1-com-instalar-vscode-en-ubuntu-18)***
>
>***[2. Com utilitzar Git](https://github.com/Maxim1erDAM/Unitat-4/blob/master/Readme.md#2-com-utilitzar-git)***
>***[3. Make i el fitxer Makefile](https://github.com/Maxim1erDAM/Unitat-4/blob/master/Readme.md#3--make-i-el-fitxer-makefile)***
#    **-Activitat pràctica-**



# UNITAT 4. Automatització amb Make.


## 1.-Com instalar Git i Make en Ubuntu 18.

>***`Actualizar llistat de repositoris de Ubuntu:`***  

sudo apt update

>***`Instalar git:`***  

sudo apt install git


>***`Instalar gcc i make:`***  

sudo apt install gcc make

## 2.-Com utilitzar Git.

>***`1.Descarregar el nostre repositori complet de Github a un directori per a treballar:`***  
>***`El nom del repositori deu ser el mateix que el repositori del sistema local. En aquest cas, será “Unitat-4”. Per aixó, abans que res, hi ha que iniciar sessió en Github al introduir la comanda.
Una vegada fet aixó es creará el repositori i será posible pujar o sincronitzar el contingut del repositori local en el repositori de GitHub. Per a conectar el directori al repositori remot de GitHub hi ha que executar la comanda "git remote add origin git clone https://github.com/USUARIGITHUB/REPOSITORI.git" `***  


>***`Eixemple, sincronizant el repositori dins de un directori anomenat "EJERCICIO", amb la comanda "git clone https://github.com/USUARIGITHUB/REPOSITORI.git":`***  

cd EJERCICIO/

git clone https://github.com/USUARIGITHUB/REPOSITORI.git

>***`En el meu cas:`***  

git clone https://github.com/Maxim1erDAM/Unitat-4.git



>***`2.Després de descarregar-lo, ens situarem en el directori i sincronitzarem el directori amb el repositori de Github.`***  
https://github.com/USUARIGITHUB/REPOSITORI.git" :`***  

>***`Eixemple:`***  



cd Unitat-4/

git remote add origin https://github.com/Maxim1erDAM/Unitat-4.git

## 3.-Make i el fitxer Makefile
>***`3.Modificarem els fitxers, en este cas son els fitxers escrits en C del exercici "Calcula":calc.c, calc.h i calcula.c amb companyia del fitxer Makefile de make.`***  

![ImatgeFitxers](Imatges/CAPTURA%20FINAL%20FITXERS.png)

>***`3. Executem els TARGETS del makefile amb "sudo make TARGET": `***  

![ImatgePostCompilacioTARGETSPart1](Imatges/Eixeple%20de%20compilacio%20i%20targets%20de%20Makefile%20i%20CMAKE%20part%201.png)

![ImatgePostCompilacioTARGETSPart2](Imatges/Eixeple%20de%20compilacio%20i%20targets%20de%20Makefile%20i%20CMAKE%20part%202.png)
>***`Al modificar els fitxers tindrem que sincronizarlos amb el nostre repositori local de GIT amb "git add" : `***  

git add NOMDEFITXER

>***`Una vegada fet aixó tindrem que escriure un COMMIT per a anotar els canvis que hem realitzat:`***  
>***`Eixemple:`***  


![ImatgePushARepoPart1](Imatges/Git-Github%20PARTE%201.png)
![ImatgePushARepoPart2](Imatges/Git-Github%20PARTE%202.png)

>***`Crearem un fitxer .gitignore per a que no incluisca els fitxers .o compilats de el directori del repositori:`***  
>***`Eixemple:`***  
![CreacioArchiu.gitignore](Imatges/Creació%20de%20fitxer%20.gitignore%20incluint%20commit%20i%20fent%20push%20al%20branch%20master.png)

>***`Así un eixemple de push de les Imatges del ejercici:`***  
>***`Eixemple:`***  
![PujadaD'imatges](Imatges/captura%20final%20edd%20pujada%20imatges.png)









