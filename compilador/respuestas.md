1. Escriban qué esperan de cada uno de los pasos
   Pre-procesador: `make preprocessing`: identifica tipo de variables y funciones
2. Compilacion I: `make assembler`: transcribe el códigoa lenguaje assembler
3. Compilacion II: `make object`: trascribe del lenguaje assembler a binario
4. Linkeo: `make executable: vincular a nuestro código todo el código que proviene de librerías, en el caso de ser estático copia el codigo del obget al ejecutable , en caso de ser dinámico utiliza un puntero a  la libreria del sistema
2. ¿Qué agregó el preprocesador?: todo el archivo stdio.h
3. Identificar en la rutina de assembler las funciones: son llamadas en las call ad_number y printf 
4. Explicar qué quieren decir los símbolos que se crean en el objeto: figuran las funciones del programa y las externas con sus descriptores
5. ¿En qué se diferencian los símbolos del objeto y del ejecutable? figuran mas descriptores y el link a la función printf
