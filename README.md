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
   
