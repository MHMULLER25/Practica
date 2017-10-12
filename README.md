# CIFRADO CÉSAR


## Objetivos del Programa:
<p> Crea una web que pida, por medio de un prompt(), una frase al usuario y devuelva el mismo mensaje encriptado según el algoritmo de Cifrado César con el parámetro de desplazamiento de 33 espacios hacia la derecha</p>

<p>Por ejemplo:</p>

<p>Texto original: ABCDEFGHIJKLMNOPQRSTUVWXYZ</p>
<p>Texto codificado: HIJKLMNOPQRSTUVWXYZABCDEFG</p>


### Consideraciones Específicas</p>

<p>Tu programa debe ser capaz de cifrar y descifrar tanto letras mayúsculas como minúsculas. La fórmula para descifrar es: (x - n) % 26</p>
<p>Tu código debe estar compuesto por 2 funciones con los siguientes nombres: cipher y decipher </p>
<p>El usuario no debe poder ingresar un campo vacío o que contenga números. </p>

## Ejemplo
<p> Supongomos que queremos cifrar la letra A , en la tabla esta en la posicion 0<p>
  
![cifradoa](https://user-images.githubusercontent.com/32310087/31506149-3f4f0e8e-af3c-11e7-8e43-9f18033c9127.PNG)


<p> Contamos 33 espacios hacia la derecha y obtenemos la letra H <p>
  
 ![cifradoh](https://user-images.githubusercontent.com/32310087/31506346-bd59712a-af3c-11e7-8f50-e682b7205453.PNG)


<p> La formula que usaremos es :
  
![formula](https://user-images.githubusercontent.com/32310087/31506436-0b8c8684-af3d-11e7-8cd8-98f825bef419.PNG)

<p> Pero para las compuadoras utilizan el codigo ASCII para representrar los caracteres, en el codigo ASCII el alfabeto empieza desde 65.La nueva formula sera: <p>
  
 ![formulanueva](https://user-images.githubusercontent.com/32310087/31506478-23100650-af3d-11e7-8cd3-5abad1fd118f.PNG)
  
## Diagrama de Flujo:


## Explicación del Pseudocódigo:

## Aprendimos sobre ...

- charCodeAt : Es un método que devuelve un número indicado del carácter proporcionado 'A'.charCodeAt=65.
- String.fromCharCode(): método devuelve una caracter o cadena mediante el uso de una secuencia de valores Unicode especificada    String.fromCharCode(65)='A'.
- El código ASCII que en español significa Código Estadounidense Estándar para el Intercambio de Información,este código está basado integralmente en el alfabeto latino que tiene distintos tipos de usos y puede tratarse de una combinación de símbolos en el marco de un sistema establecido que cuenta con un cierto valor.

