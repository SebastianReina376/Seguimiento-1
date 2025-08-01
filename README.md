## **Seguimiento-1**

**Descripción del formato**

 El formato GFF3 (General Feature Format versión 3) es un estándar ampliamente utilizado para representar anotaciones genómicas en archivos de texto plano. Posee 9 columnas delimitadas por tabulación. Muy usado en genómica estructural. 

 Aquí se muestra cada columna presente en el formato. 
 
Columna 1: "seqid". Hace referencia al nombre de la secuencia. Lo cual está relacionado con las coordenadas.

Columna 2: "source". Origen del feature. 

Columna 3: "type". Tipo de feature.

Columna 4: "start". Posición de inicio del feature.

Columna 5 "end". Posicion final del feature.

Columna 6 "score". Score del feature.

Columna 7 "strand". Hebra del feature.

Columna 8 "phase". Fase del feauture. Indica donde comienza el siguiente codon con respecto al 5' end.

Columna 9 "attributes". Atributos del feature.

**Descripción del Organismo**

La tuátara común (Sphenodon punctatus) es una especie de saurópsido esfenodontos de la familia Sphenodontidae. Es comúnmente confundido con los largatos sin embargo pertenecen a otro orden. Aquí se muestran algunas de sus características como: sus dientes fusionados con su mandíbula, promedio de longitud de 50 cm de largo y pesando entre 0.5 a 1 kg. Es capaz de sobrevivir a temperaturas más bajas que otros reptiles. Otra característica es que son animales longevos, llegando a vivir más de un siglo, sin embargo, se reproducen lentamente alcanzando la madurez sexual a los 10 años de vida. 

**Respuesta a preguntas**

Es indispensable aclarar antes de leer el archivo, que se usara el punto (.) como separador de miles.

1. ¿Cuántos features contiene el archivo?

   El archivo de Sphenodon Punctatus contiene 20 features sin contar cuantas veces aparece el feature. Contando las repiticiones contiene un total de 761.973.
   
2. ¿Cuántas regiones de la secuencia (cromosomas) contiene el archivo?

   El archivo contiene 16.536 regiones.
   
3. ¿Cuántos genes están listados en el organismo?

   Al realizar el análisis se encontraron varios features con presencia de la palabra gene. Se realizó una búsqueda y se encontró que la mayoría de lo otros que menciona el archivo     son secuencias que no se traducirán, y aunque el gene también posee secuencias que no se traduciran es la forma más cercana de saber que de esos habrá producción de proteínas. Por lo tanto, los mencionados como respuesta serán solo los que aparezcan como gene dando un total de 17.648.
   
4. ¿Cuál es el top 10 de tipo de features (columna 3 más anotados en el genoma)?

   1. 252.872 exon
      
   2. 239.450 CDS
      
   3. 187.067 biological_region
      
   4.  25.240 mRNA
      
   5.  17.648 gene
      
   6.  16.536 region
       
   7.  11.573 five_prime_UTR
       
   8.   8.195 three_prime_UTR
       
   9.     910 ncRNA_gene
   
   10.    776 pseudogenic_transcript

**Referencias**

Tuátara (Sphenodon punctatus). (n.d.). NaturaLista Colombia. https://colombia.inaturalist.org/taxa/200834-Sphenodon-punctatus

Rodríguez, H. (2022, November 4). Descubren un reptil prehistórico extinto que vivía entre los dinosaurios. National Geographic España. https://www.nationalgeographic.com.es/ciencia/descubren-reptil-prehistorico-extinto-que-vivia-entre-dinosaurios_18988
