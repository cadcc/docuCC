# Como edito lo que esta en el FAQ del CaDCC?

El FAQ del CaDCC, al igual que este, es un repo en el github de la organización CaDCC.
Para editarlo pide permiso a tu sysadmin favorito.

## Ok tengo permiso, ahora que?

Dentro de la carpeta docs está todo lo que necesitas editar.

* Cada archivo `.md` es un FAQ distinto.
* Cada carpeta es una división de FAQ's.
* Los FAQ's tienen el nombre del archivo `.md`
* Para ver como escribir en un archivo `.md` aquí hay un tutorial:

```
# Esto es otra prueba!

Puedo escribir en _cursiva_, **Negrita**, <s>texto tachado</s> o `código`.

~~No se tacha así~~

Hago párrafos con **doble enter**

En tu cara, **LaTeX**! 

## Bloques de código
```java
public static void main(String[] args){
    System.out.println("hola!");
}
```

## Listas

### Listas Numeradas:

1. Hola
1. Puedo colocar puros unos e igual se numera bien
2. O puedo colocar un número cualquiera
40. no?

* También están las listas de este estilo
* hola
  - también son indentables y se pueden usar guiones
    1. Y se puede ir alternando
  - hola hola hola
* hola

También puedes | Hacer tablas
------------ | -------------
No tienen que quedar lindas acá | Lo de arriba es un header, por eso los guiones
Hola! | lalala

# Fotos!

![Las imagenes van en la carpeta _\_static_](_static/s12.png)

### También puedes citar texto:

> Que el movimiento no sea de tu cuello sino que cuerpo o torso completo.
> _Steve Jobs_

[Más info de todo esto acá](https://guides.github.com/features/mastering-markdown/) (Sirve todo menos los emoji, el tachado de texto y las listas :c )
```
