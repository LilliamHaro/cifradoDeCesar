##README
###Cifrado Cesar

-Pseudocódigo del programa para el cifrado Cesar
  -Proceso del Algoritmo:
      -Pedir el input en letras
      -Verificar que el input no esté vacío con un if
      -Verificar que no se haya ingresado números en el input
      -Convertir cada letra del input a su código ascii con charCodeAt
      -Aplicar la fórmula de cifrado de cesar al código ascii anterior
      -Con el resultado de la fórmula y con fromCharCode obtener la nueva letra cifrada
      -Almacenar la letra en un array
      -Devolver ese array convertido a String usando join('')
