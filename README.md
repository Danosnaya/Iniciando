# Documentacion

El archivo describe algunos de las principales comandos que linux acepta.

## Inicio

Se debe iniciar la terminal de linux que sera la ejecutora de comandos 

### ls

Comando utilizado para identificar los directorios y/o archivos que estan 

```
daniel@osnaya:~$ ls

Desktop   Music    Picture   Documents
```

### cd

comando para ingresar a algun diectorio de 

```
daniel@osnaya:~$ cd Documents
```

Se ingresa a dicho directorio

```
daniel@osnaya:~/Documents$
```
### mkdir

Comando utilizado para crear nuevos  directorios.

```
daniel@osnaya:~$ mkdir Dowloads
daniel@osnaya:~$ ls

Desktop   Music    Picture   Documents   Dowloads
```

### rmdir

Comando utilizado para eliminar directorios que se encunetren vacios.

```
daniel@osnaya:~$ rmdir Dowloads
daniel@osnaya:~$  ls

Desktop   Music    Picture   Documents   
```

### rm -r

Comando utilizado para eliminar directorios que contienen algun archivo.

```
daniel@osnaya:~$  rm -r Dowloads/
daniel@osnaya:~$  ls

Desktop   Music    Picture   Documents   
```

### touch

Comando utilizado para crear nuevos archivos sin salir del terminal.

```
daniel@osnaya:~$  touch instruccion.txt
daniel@osnaya:~$  ls

Desktop   Music    Picture   Documents   
instruccion.txt
```

### pico,nano

Comando utilizado para editar archivos,te abre un editor de textos.

```
daniel@osnaya:~$  pico instruccion.txt

```

### echo 

Comando utilizado para asignartexto a un archivo sin abrir alguna ventana de editor de texto.

```
daniel@osnaya:~$  echo Hola, mensaje de prueba >> instruccion.txt
daniel@osnaya:~$  cat instruccion.txt
Hola, mensaje de prueba

```

### cat

Comando utilizado para ver el contenido de una archivo.

```
daniel@osnaya:~$  echo Hola, mensaje de prueba >> instruccion.txt
daniel@osnaya:~$  cat instruccion.txt
Hola, mensaje de prueba

```

### pwd

Comando que imprime la ruta en donde se encuntra o la ubicacion en cuanto a directorios


```
daniel@osnaya:~$ pdw
/home/Desktop

```

### clear 

Limpia la pantalla de tu terminal  

```
daniel@osnaya:~$ clear

```

### wc 

Imprime en pantalla la cantidad de saltos de lineas, palabras y bytes totales que contenga un archivo.


```

daniel@osnaya:~$ wc archivo.txt
2  8  32

```

### tail

Comando que muestra en pantalla las ultimas lineas de un archivo.

```
daniel@osnaya:~$ cat hola.txt
Hola
mundo
gran
dia
daniel@osnaya:~$ tail -n2 hola.txt
gran
dia

```

###head 

Comando que muestra en pantalla las primeras lineas de un archivo.

```
daniel@osnaya:~$cat hola.txt
hola
mundo
gran
dia
daniel@osnaya:~$head -n2 hola.txt
hola 
mundo

```



