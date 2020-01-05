# **1ER DAM. Desarrotllament D'Aplicacions Multiplataforma. EDD. Entorns de Desenvolupament.**

***2019-Editat per Máxim Sánchez Porta***


# Index:



>### UNITAT 4. Automatització amb Make.
>
>***[1.-Com instalar Git i Make en Ubuntu 18.](https://github.com/Maxim1erDAM/EDD/blob/master/Unitat%202/Unitat2.md#1-com-instalar-vscode-en-ubuntu-18)***
>

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
>***`Eixemple:`***  

cd EJERCICI/

git clone https://github.com/USUARIGITHUB/REPOSITORI.git

>***`En el meu cas:`***  
git clone https://github.com/Maxim1erDAM/Unitat-4.git



>***`2.Després de descarregarlo ens situarem en el directori i sincronitzarem el directori amb el repositori de Github :`***  
>***`Eixemple:`***  
El nom del repositori deu ser el mateix que el repositori del sistema local. En aquest cas, será “Unitat-4”. Per aixo, abans que res, hi ha que iniciar sessió en Github al introduir la comanda.

Una vegada fet aixó es creará el repositori i será posible pujar o sincronitzar el contingut del repositori local en el repositori de GitHub. Per a conectar el directori al repositori remot de GitHub hi ha que executar la comanda:

cd Unitat-4/
git remote add origin https://github.com/Maxim1erDAM/Unitat-4.git

![PujadaD'imatges](Imatges/captura%20final%20edd%20pujada%20imatges.png)



![ImatgePushARepoPart1](Imatges/Git-Github%20PARTE%201.png)
![ImatgePushARepoPart2](Imatges/Git-Github%20PARTE%202.png)


![ImatgeCompilacioPart1](Imatges/Eixeple%20de%20compilacio%20i%20targets%20de%20Makefile%20i%20CMAKE%20part%201.png)


![ImatgeFitxers](Imatges/CAPTURA%20FINAL%20FITXERS.png)


