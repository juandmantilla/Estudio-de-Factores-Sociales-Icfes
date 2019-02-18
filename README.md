Proyecto-Icfes-2018
Proyecto enfocado a la predicción de puntajes Saber 11 , tomando como referencia factores sociales cuantitativos relevantes y determinantes. Los datos son proporcionados por la plataforma www.datos.gov.co. A través del siguiente enlace podrá exportar el archivo en formato CSV https://www.datos.gov.co/Educaci-n/Saber-11-2018-2/m2nt-jw2h

_La modificación de los datos es necesaria. Se realizaron cambios en los campos por valores numéricos totalmente relacionados con los valores de las características:_

1. Los valores del campo ESTU_GENERO han sido reemplazados por 0 (femenino) y 1 (masculino).
2. Los valores del campo ESTU_DEPTO_RESIDE han sido reemplazados por valores numéricos con respecto al orden alfabético de los nombres de los departamentos
3. FAMI_ESTRATOVIVIENDA: 0 (Sin estrato),...,6 (Estrato 6)
4. FAMI_TIENEINTERNET: Si (1), No (0)
5. FAMI_TIENECOMPUTADOR: Si (1), No (0)
6. FAMI_SITUACIONECONOMICA: Peor (0), Igual(1), Mejor(2)

_Los siguientes valores (medido en minutos) corresponden a la media de los extremos de los rangos otorgados por el archivo:_

1. ESTU_DEDICACIONLECTURADIARIA: 30 minutos o menos (15), Entre 30 y 60 minutos (45), Entre 1 y 3 horas (120), Mas de 2 horas (120), No lee por entretenimiento (0)
2. ESTU_DEDICACIONINTERNET: No navega (0), 30 minutos o menos (15), Entre 30 y 60 minutos (45), Entre 1 y 3 horas (120), Mas de 3 horas (180)

_Además de añadir el "factor social" que radica en un puntaje dado por la media de cada una de las características a excepción del género y el departamento donde reside. Deducimos que esta representación aproximada se correlacione con los puntajes obtenidos en las pruebas saber 11 2018-2. 