# JavaScriptCourse

## Escritura de código

  Los identificadores deben comenzar con:
   - Una letra o
   - Un signo de dolar $ o
   - Un guión bajo _
   - Nunca con números o caracteres especiales.
   
   Usa snake_case en:
   - Nombre de archivos:
   ~~~
   mi_archivo_javascript.js
   ~~~
   Usa UPPER_CASE en:
   - Constantes:
   ~~~
   const UNA_CONSTANTE = "Soy una constante",
   PI = 3.141592653589793;
   ~~~
   Usa UpperCamelCase en:
   - Clases:
   ~~~
   class SerHumano {
    constructor(nombre, genero) {
      this.nombre = nombre;
      this.genero = genero;
    }

    miNombreEs() {
    return `Mi nombre es ${this.nombre}`;
    }
   }
   ~~~
   Usa lowerCamelCase en:
   - Objetos:
   ~~~
   const unObjeto = {
   nombre: "Daniel",
   email: "esobare361@gmail.com",
   };
   ~~~
   - Primitivos:
   ~~~
   let unaCadena = "Hola Mundo",
   unNumero = 19,
   unBoolean = true;
   ~~~
   - Funciones:
   ~~~
   function holaMundo(nombre) {
   alert(`Hola mundo ${nombre}`);
   }
   holaMundo("Daniel");
   ~~~
   - Instancias:
   ~~~
   const ajax = new XMLHttpRequest(),
   jon = new SerHumano("Daniel", "Hombre");
   ~~~
   
Palabras Reservadas:
~~~
A: abstract
B: boolean, break, byte
C: case, catch, char, class, const, continue
D: debugger, default, delete, do, double
E: else, enum, export, extends
F: false, final, finally, float, for, function
G: goto
I: if, implements, import, in, instanceof, int, interface
L: let, long
N: native, new, null
P: package, private, protected, public
R: return
S: short, static, super, switch, synchronized
T: this, throw, throws, transient, true, try, typeof
V: var, volatile, void
W: while, with
~~~
