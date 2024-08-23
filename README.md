<img src="/src/portada_02.gif" alt="Portada" width="100%">

# 📜 PLANTILLAS PARA READMES

## 📄 PLANTILLA BASE

### PARTES

Un README.md atractivo debe contener la mayoría de las siguientes partes:

<table>
    <tr>
        <td>1. Título e imagen de portada</td>
        <td>7. Acceso al Proyecto</td>
    </tr>
    <tr>
        <td>2. Insignias</td>
        <td>8. Tecnologías utilizadas</td>
    </tr>
    <tr>
        <td>3. Índice</td>
        <td>9. Personas Contribuyentes</td>
    </tr>
    <tr>
        <td>4. Descripción del Proyecto</td>
        <td>10. Personas Desarrolladoras del Proyecto</td>
    </tr>
    <tr>
        <td>5. Estado del proyecto</td>
        <td>11. Licencia</td>
    </tr>
    <tr>
        <td>6. Demostración de funciones y aplicaciones</td>
        <td></td>
    </tr>
</table>

## :id: ELEMENTOS

Los elementos que puedes incluir en el README.md se detallan a continuación, si quieres sugerir alguno que no está incluido, contáctame para agregarte en el equipo de contribución.

### 1. ENCABEZADOS

Los encabezados describen a grandes rasgos y destacan el principio y fin de las secciones que componen una descripción del README o de la documentación de un repositorio.

  <pre> 
      # Encabezado primer nivel
      ## Encabezado segundo nivel
      ### Encabezado tercer nivel
  </pre>

### :eyes: EJEMPLOS

#        Encabezado primer nivel
##           Encabezado segundo nivel
###              Encabezado tercer nivel
##  

### 2. ESTILOS DE TEXTO

Los estilos de texto permiten dentro del texto destacar, resaltar o diferenciar algunas palabras u oraciones del resto para que se ponga más atención a ciertas partes o se las recuerde con especial atención por su importancia.

| Estilo  | Muestra | Código  |
| ------------- | ------------- | ------------- |
| Bold | **Texto grueso** | ``` **Texto grueso** ``` |
| Cursiva | *Texto cursiva* | ``` *Texto cursiva* ``` |
| Tachado | ~~Texto tachado~~ | ``` ~~Texto tachado~~ ``` |
| Subscript | Subindice<sub>A</sub> | ``` Subindice<sub>A</sub> ``` |
| Superscript | Superindice<sup>2</sup> | ``` Superindice<sup>2</sup> ``` |
##  
### 3. SECCIÓN DESTACADA

El único inconveniente es que GitHub Markdown no soporta directamente el uso de estilos CSS y no hay la versión en español para las cabeceras de cada cita o bloque, esperemos pronto añadan la versión en español.

### Sección destacada estandar

Es un bloque de texto que se diferencia del resto de párrafos.

> No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original.

** Código Markdown **
```
> No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original.
```
##  

### Sección destacada regular
> [!NOTE]
> Useful information that users should know, even when skimming content.

**Código**
```
> [!NOTE]
> Useful information that users should know, even when skimming content.
```
##  

### Sección destacada regular alternativa
> [!TIP]
> Helpful advice for doing things better or more easily.

**Código**
```
> [!TIP]
> Helpful advice for doing things better or more easily.
```
##  

### Sección destacada importante
> [!IMPORTANT]
> Key information users need to know to achieve their goal.

**Código**
```
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
```
##  

### Sección destacada advertencia
> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

**Código**
```
> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.
```
##  

###  Sección destacada precaución
> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

**Código**
```
> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
##  

### 4. DESTACAR TEXTO

En un párrafo se puede usar comilla simple.

Use `git status` to list all new or modified files that haven't yet been committed.

**Código**
```
Use `git status` to list all new or modified files that haven't yet been committed.
```

Se puede formatear texto en un bloque con triple comilla, como en el siguiente ejemplo.

```
git status
git add
git commit
```

**Código**
```
    ```
    git status
    git add
    git commit
    ```
```

Si queremos que el bloque de texto se muestre con colores diferenciados podemos hacer referencia al lenguaje.

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

**Código**
````
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
````
##  

### 5. VÍNCULOS O ENLACES

Puede crear un vínculo en línea escribiendo su texto entre corchetes [ ] y escribiendo la URL entre paréntesis ( ). También puede usar el método abreviado de teclado CTRL + K cuando haya seleccionado texto para crear un vínculo.

También puedes crear un hipervínculo de Markdown resaltando el texto y usando el método abreviado de teclado CTRL + V. Si quieres reemplazar el texto por el vínculo, usa el método abreviado de teclado CTRL + SHIFT + V.

**Ejemplo**

This site was built using [GitHub Pages](https://pages.github.com/).

**Código**
```
This site was built using [GitHub Pages](https://pages.github.com/).
```

Se puede crear un enlace a cualquier título o subtítulo en Markdown copiando el enlace del ícono que aparece a la izquierda del título o subtítulo cuando se desliza el puntero del mouse sobre el encabezado de la sección.

![imagen](https://github.com/user-attachments/assets/a0dd2644-654f-4e31-a3e8-a6148b61c0e6)

**Ejemplo**

[Ir a Elementos de este README.md](https://github.com/Disenandowebs/readmes?tab=readme-ov-file#id-elementos)

**Código**
```
[Ir a Elementos de este README.md](https://github.com/Disenandowebs/readmes?tab=readme-ov-file#id-elementos)
```

Otro tipo de vínculos son los enlaces relativos y rutas de imagen en los archivos representados para ayudar a que los lectores naveguen hasta otros archivos de tu repositorio.

Un enlace relativo es un enlace que es relativo al archivo actual. Por ejemplo, si tiene un archivo Léame en la raíz del repositorio y tiene otro archivo en docs/CONTRIBUTING.md, el vínculo relativo a CONTRIBUTING.md en el archivo Léame podría tener este aspecto:

**Código**
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

Puede mostrar una imagen agregando ! y ajustar el texto alternativo en [ ]. El texto alternativo es un texto corto equivalente a la información de la imagen. Luego, escribe el vínculo de la imagen entre paréntesis ().

**Código**
```
![Descripción de Imagen](https://myoctocat.com/assets/images/base-octocat.svg)
```

> [!TIP]
> Cuando quieras mostrar una imagen incluida en el repositorio, usa vínculos relativos en vez de absolutos.

##  

### 6. LISTAS Y TABLAS

Puedes crear una lista sin ordenar. Para ello, coloca -, * o + antes de una o más líneas de texto.

- George Washington
* John Adams
+ Thomas Jefferson

**Código**
```
- George Washington
* John Adams
+ Thomas Jefferson
```

Para ordenar tu lista, antecede cada línea con un número.

1. James Madison
2. James Monroe
3. John Quincy Adams

**Código**
```
1. James Madison
2. James Monroe
3. John Quincy Adams
```

Puedes crear una lista anidada al dejar sangría en uno o más elementos de la lista debajo de otro elemento.

1. First list item
   - First nested list item
     - Second nested list item

**Código**
```
1. First list item
   - First nested list item
     - Second nested list item
```

Para crear una lista de tareas, debe añadir como prefijo un guion y espacio, seguido de [ ] a los elementos de la lista. Para marcar una tarea como completada, use [x].

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

**Código**
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```

Si la descripción de un elemento de la lista de tareas comienza por un paréntesis, necesitará agregar el carácter de escape \:

- [ ] \(Optional) Open a followup issue

**Código**
```
- [ ] \(Optional) Open a followup issue
```

Para crear tablas se utiliza estructuras sencillas para obtener algo como lo siguiente

**Código**

| Columna1 | Columna2 | Columna3  |
| ------------- | ------------- | ------------- |
| Fila 1 | Fila 1 | Fila 1  |
| Fila 2 | Fila 2 | Fila 2  |
| Fila 3 | Fila 3 | Fila 3  |

**Código**
```
| Columna1 | Columna2 | Columna3  |
| ------------- | ------------- | ------------- |
| Fila 1 | Fila 1 | Fila 1  |
| Fila 2 | Fila 2 | Fila 2  |
| Fila 3 | Fila 3 | Fila 3  |
```

### 7. EMOJIS

Puedes agregar emoji a la escritura escribiendo `:CodigoDeEmoji:`, dos puntos seguidos al principio y al final del nombre ó código del emoji.

**Ejemplo**

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

**Código**
```
@octocat :+1: This PR looks great - it's ready to merge! :shipit:
```

### 8. PÁRRAFOS O SEPARACIÓN DE LÍNEAS DE TEXTO

Puedes crear un nuevo párrafo al dejar una línea en blanco entre las líneas de texto.

### 9. NOTAS AL PIE

Puedes agregar notas al pie para tu contenido si utilizas esta sintaxis de corchetes.

**Ejemplo**

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

**Código**
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```

> [!NOTE]
> En el anterior ejemplo, las notas al pie están escritas directamente después de sus referencias en los párrafos o líneas de texto, pero éstas automáticamente son llevadas al final del REAMDE.md cuando se visualizan con Markdown.












https://docs.github.com/es/get-started/accessibility/keyboard-shortcuts

### HERRAMIENTAS

Las herramientas son plataformas que te ayudan a crear algunos elementos en MarkDown mucho más fácil. Te dejo algunas:
- Editor online de HTML: https://onlinehtmleditor.dev/
- Generador de tablas en diferentes formatos: https://www.tablesgenerator.com/

## PLANTILLA 01

<pre> # El título aquí </pre>

<pre> Una imagen como portada </pre>


https://www.aluracursos.com/blog/como-escribir-un-readme-increible-en-tu-github
