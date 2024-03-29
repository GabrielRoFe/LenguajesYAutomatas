Vera Rodríguez Héctor Gabriel.

# EXPRESIÓN REGULAR:

Las expresiones regulares están estrechamente relacionadas con los autómatas finitos no deterministas y pueden considerarse una alternativa, que el usuario puede comprender fácilmente, a la notación de los AFN para describir componentes de software. Por tanto, las expresiones regulares sirven como lenguaje de entrada de muchos sistemas que procesan cadenas. Algunos ejemplos son los siguientes:

1. Comandos de búsqueda tales como el comando grep de UNIX o comandos equivalentes para localizar cadenas en los exploradores web o en los sistemas de formateo de texto.
2. Generadores de analizadores léxicos, como Lex o Flex. Recuerde que un analizador léxico es el componente de un compilador que divide el programa fuente en unidades lógicas o sintácticas formadas por uno o más caracteres que tienen un significado.

La importancia de las expresiones regulares radica en su capacidad para describir patrones de cadenas de caracteres de manera concisa y precisa.

# EJEMPLO: 

Encuentra la expresión regular para el conjunto de cadenas sobre el alfabeto {a, b, c} que tiene al menos una a y al menos una b.

**Solución:**
*c ∗a(a + c) ∗b(a + b + c) ∗ + c ∗b(b + c) ∗a(a + b + c) ∗*

Ósea, cuando la primera a esta antes que la primera b o cuando la primera b esta antes de la primera a.

# CASOS DE USO:
  
Las expresiones regulares tienen una amplia gama de casos de uso en diversos campos de la informática. Algunos de los casos de uso más comunes son:

1.  ***Validación de datos***: Las expresiones regulares se utilizan para validar la entrada de datos en formularios web o aplicaciones. Por ejemplo, se pueden utilizar para verificar si una dirección de correo electrónico, un número de teléfono o un código postal tienen el formato correcto.
    
2.  ***Búsqueda y extracción de información***: Las expresiones regulares se utilizan para buscar patrones específicos dentro de grandes conjuntos de datos. Esto es útil para encontrar palabras clave, números, fechas u otra información relevante en un texto.
    
3.  ***Manipulación de texto***: Las expresiones regulares permiten realizar operaciones avanzadas de búsqueda y reemplazo en texto. Se pueden utilizar para encontrar y reemplazar palabras o frases específicas, eliminar o modificar partes del texto, y realizar otras transformaciones complejas.
    
4.  ***Análisis léxico en compiladores***: En la teoría de la compilación, las expresiones regulares se utilizan para definir los tokens de un lenguaje de programación y realizar el análisis léxico, que es la primera fase del proceso de compilación.
    
5.  ***Procesamiento de datos estructurados***: Las expresiones regulares se utilizan para extraer información relevante de archivos de texto o documentos con un formato específico, como registros de archivos de registro, archivos de configuración, documentos XML, JSON, etc.
    
6.  ***Manipulación de cadenas en programación***: Las expresiones regulares se utilizan en la programación para realizar operaciones avanzadas de búsqueda y manipulación de cadenas. Por ejemplo, en Python, JavaScript y otros lenguajes, las expresiones regulares se utilizan junto con funciones como `match()`, `search()`, `replace()`, etc.
    
7.  ***Búsqueda y filtrado en herramientas de texto y editores de código***: Muchos editores de texto y entornos de desarrollo integrados (IDE) admiten búsquedas y filtrado basados en expresiones regulares, lo que permite a los usuarios realizar búsquedas avanzadas y manipulaciones de texto en grandes proyectos de código.

# CONCLUSIÓN:
En pocas palabras su importancia es grande, sirven para poder buscar en grandes cantidades de datos cosas puntuales, es como un poder, no se comparan con el típico buscador ctrl+f, estas poseen mas herramientas y hacen que se pueda encontrar datos con exactitud también se pueden poner tan complejas cuando estras tabajando con csv y demás pero cuando las dominas son una navaja suiza: "solucionan gran parte del trabajo"

# REFERENCIAS:

_Expresiones Regulares_. (s/f). Edu.ar. Recuperado el 19 de marzo de 2024, de https://cs.famaf.unc.edu.ar/~hoffmann/md18/10.html

_Expresiones regulares_. (s/f). Gitlab.io. Recuperado el 19 de marzo de 2024, de https://ivanvladimir.gitlab.io/lfya_book/docs/02lam%C3%A1quinasinmemoria/03expresionesregulares/

Rosas, O. (2017, enero 29).  _Lenguajes y Expresiones Regulares_. Compilando Conocimiento. https://compilandoconocimiento.com/2017/01/29/expresiones-reguales/
