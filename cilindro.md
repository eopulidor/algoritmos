> **Algoritmo** Volumen_de_un_cilindro
	>> **escribir** "radio_en_metros";
	>> **escribir** "altura_en_metros";
	>> **definir** radio_en_metros,altura_en_metros,factor1,producto Como Real;
	>> **leer** radio_en_metros;
	>> **leer** altura_en_metros;
	>> *factor1* <- 3.1416;
	>> *producto* <- (factor1*(radio_en_metros*radio_en_metros))*altura_en_metros;
	>> **Escribir** "factor1", "por" , "radio_en_metros", "por" , "radio_en_metros" , "por" , "altura_en_metros" , "=" , producto;
> **FinAlgoritmo**

>**Algoritmo** Area_de_un_cilindro
	>>**Escribir** "radio_en_metros";
	>>**escribir** "altura_en_metros";
	>>**definir** radio_en_metros,altura_en_metros,factor2,producto Como Real;
	>>**Definir** factor1 Como Entero;
	>>**Leer** radio_en_metros;
	>>**Leer** altura_en_metros;
	>>*factor1* <- 2;
	>>*factor2* <- 3.1416;
	>>*producto* <- (factor1*factor2*radio_en_metros)*(radio_en_metros+altura_en_metros);
	>>**Escribir** "factor1","por","factor2","por","radio_en_metros","por","radio_en_metros","mas","altura_en_metros","=",producto;
>**FinAlgoritmo**
