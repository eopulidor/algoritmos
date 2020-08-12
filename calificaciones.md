**Escribir** "nota_parcial_1";

   **Escribir** "nota_parcial_2";

   **Escribir** "participacion_en_clase";

   **Escribir** "nota_examen_final";

   **Definir** nota_parcial_1,nota_parcial_2,participacion_en_clase,nota_examen_final,factor1,factor2,factor3,producto Como Real;

   **leer** nota_parcial_1;

   **leer** nota_parcial_2;

   **Leer** participacion_en_clase;

   **Leer** nota_examen_final;

   *factor1* <-0.25;

   *factor2* <-0.2;

   *factor3* <-0.3;

   *producto* <- (nota_parcial_1*factor1)+(nota_parcial_2*factor1)+(participacion_en_clase*factor2)+(nota_examen_final*factor3);

**Escribir**"nota_parcial_1","por","factor1","mas","nota_parcial_2","por","factor1","mas","participacion_en_clase","por","factor2","mas","nota_examen_final","por","factor3","=",producto;

**FinProceso**
