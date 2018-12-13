# Documentacion

El archivo describe algunos de las principales comandos que linux acepta.

## Inicio

Se debe iniciar la terminal de linux que sera la ejecutora de comandos 

### ls

Comando utilizado para identificar los directorios y/o archivos que estan 

```
nayso@Alok-aspire:~$ ls

Desktop   Music    Picture   Documents
```

### cd

comando para ingresar a algun diectorio de 

```
nayso@Alok-aspire:~$ cd Documents
```

Se ingresa a dicho directorio

```
nayso@Alok-aspire:~/Documents$
```
### mkdir

Comando utilizado para crear nuevos  directorios.

```
nayso@Alok-aspire:~$ mkdir Dowloads
nayso@Alok-aspire:~$ ls

Desktop   Music    Picture   Documents   Dowloads
```

### rmdir

Comando utilizado para eliminar directorios que se encunetren vacios.

```
daniel@osnaya:~$ rmdir Dowloads
daniel@osnaya:~$ ~$ ls

Desktop   Music    Picture   Documents   
```

### rm -r

Comando utilizado para eliminar directorios que contienen algun archivo.

```
daniel@osnaya:~$ ~$ rm -r Dowloads/
daniel@osnaya:~$ ~$ ls

Desktop   Music    Picture   Documents   
```

### touch

Comando utilizado para crear nuevos archivos sin salir del terminal.

```
daniel@osnaya:~$ ~$ touch instruccion.txt
daniel@osnaya:~$ ~$ ls

Desktop   Music    Picture   Documents   
instruccion.txt
```

### pico,nano

Comando utilizado para editar archivos,te abre un editor de textos.

```
daniel@osnaya:~$ ~$ pico instruccion.txt

```

### echo 

Comando utilizado para asignartexto a un archivo sin abrir alguna ventana de editor de texto.

```
daniel@osnaya:~$ ~$ echo Hola, mensaje de prueba >> instruccion.txt
daniel@osnaya:~$ ~$ cat instruccion.txt
Hola, mensaje de prueba

```

### cat

Comando utilizado para ver el contenido de una archivo.

```
daniel@osnaya:~$ ~$ echo Hola, mensaje de prueba >> instruccion.txt
daniel@osnaya:~$ ~$ cat instruccion.txt
Hola, mensaje de prueba

```
