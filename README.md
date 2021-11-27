# Profe_20211123

# Alumne:  **Cognom, Nom**

## Teoria
|Preg.|**1**|**2**|**3**|**4**|**5**|**6**| 
|:------------:| :-------------:| :-------------:| :-------------:|:-------------:| :-------------:| :------------:| 
|**Correcte**<br><br><br><br><br>|**Sí** ☑️<br><br>No ☐<br><br><br>|**No**☑️<br><br>Sí ☐<br>**Quin?**<br><br>|**No** ☑️<br><br>Sí ☐<br><br><br>|**No** ☐<br><br>Sí☑️<br>**Quin?**<br>Fora de rang.|**Sí** ☑️<br><br>No ☐<br><br><br>|**No**☑️<br><br>Sí ☐<br>**Quin?**<br><br>|
|**Alumne**|**Sí** ☐<br><br>No ☐<br><br><br>|**No** ☐<br><br>Sí ☐<br>**Quin?**<br><br>|**No** ☐<br><br>Sí ☐<br><br><br>|**No** ☐<br><br>Sí ☐<br>**Quin?**<br><br>|**Sí** ☐<br><br>No ☐<br><br><br>|**No** ☐<br><br>Sí ☐<br>**Quin?**<br><br>|
|**Punt**|0.00|0.00|0.00|0.00|0.00|0.00|
|**Sobre**|0.25|0.5|0.25|0.25|0.25|0.25|


**Nom alumne**:

<hr>

|**Els savis són els que busquen la saviesa**<br>**els necis pensen ja haver-la trobat.**|
|:------:|
|(Napoleó Bonaparte,  15/08/1769, França - 05/05/1821, Santa Helena)|


## Teoria		(2 punts)

A partir del codi que teniu a la **pàgina 3**. Considereu que l'execució és independent de l’execució de les línies prèvies.

### Pregunta 1:	(0.25 punts)

* L'execució de les línies de la **```10```** a la **```12```** correspon a la sortida:

```
Dilluns
Dimarts
Dimecres
Dijous
Divendres
Dissabte
Diumenge
```

- [ ] Sí
- [ ] No


### Pregunta 2:	(0.5 punts)

* Apareix algun error?

- [ ] No
- [ ] Sí
  - Quin? 

<hr>

### Pregunta 3:	(0.25 punts)

* L'execució de les línies de la **```14```** a la **```18```** correspon a la sortida:

```
Lunes
Martes
Miércoles
Jueves
Viernes
Sábado
Domingo
```

- [ ] Sí
- [ ] No


### Pregunta 4:	(0.5 punts)

* Apareix algun error?

- [ ] No
- [ ] Sí
  - Quin? 

<hr>

### Pregunta 5:	(0.25 punts)
L'execució de les línies de la **```20```** a la **```24```** correspon a la sortida:
```
Monday
Tuesday
Wednesday
Thursday
Friday
Saturday
Sunday
```

- [ ] Sí
- [ ] No
	

### Pregunta 6:	(0.25 punts)

* Apareix algun error?

- [ ] No
- [ ] Sí
  - Quin? 

<hr>



Exemple d'execució, de Enunciat 8a, si l'usuari escriu el següent:
```
Entra l'índex del caràcter que vols escriure (A: 1, Z: 26, -1 per acabar): 8
Vols que el caràcter sigui majúscules (M) o minúscules (m): M
S'afegirà una "H" a la cadena.

Entra l'índex del caràcter que vols escriure (A: 1, Z: 26, -1 per acabar): 15
Vols que el caràcter sigui majúscules (M) o minúscules (m): m
S'afegirà una "o" a la cadena.

Entra l'índex del caràcter que vols escriure (A: 1, Z: 26, -1 per acabar): 35
Error! El valor ha d'estar entre 1 i 26 o -1 per acabar.

Entra l'índex del caràcter que vols escriure (A: 1, Z: 26, -1 per acabar): 12
Vols que el caràcter sigui majúscules (M) o minúscules (m): m
S'afegirà una "l" a la cadena.

Entra l'índex del caràcter que vols escriure (A: 1, Z: 26, -1 per acabar): 1
Vols que el caràcter sigui majúscules (M) o minúscules (m): m
S'afegirà una "a" a la cadena.

Entra l'índex del caràcter que vols escriure (A: 1, Z: 26, -1 per acabar): -1
La cadena final és: Hola
```


### ATENCIÓ!!!!!

Els següents aspectes que es valoraran de manera molt positiva:
Programeu de la manera més clara i eficient possible.
Poseu comentaris al vostre codi per tal d’explicar millor el que feu.
[Requisit d’obligat compliment] La vostra classe a través de la qual s’executa el vostre programa s’ha de dir, CognomNom20211123EnuXa. Per fer el lliurament dels exercicis, cal que creeu un repositori amb el nom CognomNom20211123 que sigui privat i convidar a joanpardogine. Aquest repositori pujareu els fitxers .java.
Teoria
| |
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
public class Examen_20211123_En_Teo_01 {
    public static void main(String args[]) throws Exception {
        String[] nomsCatala = {"Dilluns", "Dimarts","Dimecres",
            "Dijous", "Divendres", "Dissabte", "Diumenge"};
        String[] nomsCastella = {"Lunes", "Martes", "Miércoles",
            "Jueves", "Viernes", "Sábado", "Domingo"};
        String[] nomsAngles = {"Monday", "Tuesday", "Wednesday",
            "Thursday", "Friday", "Saturday", "Sunday"};

        for (int i = 0; i < nomsCatala.length; i++) {
            System.out.println(nomsCatala[i]);
        }

        int i = 0;
        while (i < nomsCastella.length) {
            i++;
            System.out.println(nomsCastella[i]);
        }

        i = 0;
        do {
            System.out.println(nomsAngles[i]);
            i++;
        } while (i < nomsAngles.length);

    }
}


Dels diferents enunciats, només cal que realizeu un. És a dir, si feu l'eunuciat 7a, no cal que feu ni el 7b, ni el 7c.
Enunciat 7a	(1,5 punts)
Fes un programa que crei dos arrays de caràcters, un amb les lletres majúscules (char arrMajuscules[] = new char[26];) que contingui de l'A a la Z en majúscules i un array de caràcters amb les lletres minúscules
	char arrMinuscules[] = new char[26];
que contingui de l'a a la z en minúscules. Cal fer servir dos bucles amb for diferents, un bucle per crear l'array de les lletres majúscules (arrMajuscules) i un segon per crear l'array de les lletres minúscules (arrMinuscules).
Els caràcters es codifiquen amb un nombre enter segons la taula ASCII.
Enter
Caràcter


Enter
Caràcter
65
A


97
a
66
B


98
b
67
C


99
c
...
...


...
...
88
X


120
x
89
Y


121
y
90
Z


122
z

Si la variable i és de tipus int i el seu valor és 66,  la comanda
		System.out.print((char) i); 
mostrarà un caràcter una B.
Enunciat 7b	(3 punts)
Fer el que es demana per l'enunciat A, però fent servir un únic bucle amb for per omplir els dos arrays.
Enunciat 7c	(3 punts)
Fer el que es demana per l'enunciat A, però fent servir un únic bucle amb for per omplir un únic array (char arrLletres[] = new char[52];).
Enunciat 8a (exemple d'execució a la pàgina 2)	(2,5 punts)
A partir de l'enunciat 7a, fes un programa que mostri un text per pantalla amb un seguit de lletres majúscules i minúscules. Aquest text el crearà l'usuari introduint un enter, que indicarà la posició (índex de l'array) del caràcter que vol. És a dir, si vol la lletra B, caldrà que introdueixi el número 2. Un cop entrat el número que indica la posició de la lletra, caldrà que introdueix una M majúscula per indicar si vol que la lletra que ha seleccionat, sigui majúscula o una m minúscula per indicar si vol que sigui minúscula.
El programa anirà demanant posicions de la lletra que vol, seguit de la M  majúscula o minúscula, fins que l'usuari entri un -1, moment en què el programa deixarà de demanar números i mostrarà el resultat de la cadena introduïda per l'usuari.
Per si no has pogut fer l'enunciat 7a, pots definir i inicialitzar els dos arrays:
char arrMajuscules[] = {'A','B','C','D','E','F','G','H','I',
                        'J','K','L','M','N','O','P','Q','R',
                        'S','T','U','V','W','X','Y','Z'};
char arrMinuscules[] = {'a','b','c','d','e','f','g','h','i',
                        'j','k','l','m','n','o','p','q','r',
                        's','t','u','v','w','x','y','z'};

Enunciat 8b	(5 punts)
Fer el que es demana per l'enunciat 8a, però fent servir un únic amb for que llegeixi els dos arrays.
Enunciat 8b	(5 punts)
Fer el que es demana per l'enunciat 8a, però fent servir un únic bucle for, que llegeixi un únic array anomenat (char arrLletres[] = new char[52];). És a dir, seguint el que s'ha demanat per fer l'enunciat 2B.
