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

El único inconveniente en código Markdown es que no hay la versión en español para las cabeceras de cada bloque, esperemos pronto añadan la versión en español. Aún así, se puede utilizar código HTML para obtener el mismo resultado.

### Sección destacada estandar

Es un bloque de texto que se diferencia del resto de párrafos.

> No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original.

** Código Markdown **
```
> No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original.
```

** Código HTML **
```
<div style="padding: .5rem 1rem;
           background: #f0f3f6;
           border-left: .25em solid #8b949e;
           margin: 1rem 0;">
  <p>No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original.</p>
</div>
```

##  

**Sección destacada regular**
> [!NOTE]
> Useful information that users should know, even when skimming content.

<div style="padding: .5rem 1rem;
            background: #f0f3f6;
            border-left: .25em solid #0969da;
            margin: 1rem 0;">
  <p style="display: flex; font-weight: 500; align-items: center; line-height: 1; color: #0969da;">
  <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon mr-2" aria-hidden="" style="margin-right: 0.5rem; fill: #0969da;">
    <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z">
    </path>
  </svg>
    NOTA
  </p>
  <p>Al visualizar una conversación, puedes citar automáticamente el texto en un comentario si lo resaltas y escribes R. Para citar un comentario completo, haz clic en  y, a continuación, en Citar respuesta. Para obtener más información acerca de los métodos abreviados de teclado, consulte "Accesos directos del teclado".</p>
</div>

**Código**
```
> [!NOTE]
> Useful information that users should know, even when skimming content.
```
##  

**Sección destacada regular alternativa**
> [!TIP]
> Helpful advice for doing things better or more easily.

**Código**
```
> [!TIP]
> Helpful advice for doing things better or more easily.
```

**Sección destacada importante**
> [!IMPORTANT]
> Key information users need to know to achieve their goal.

**Código**
```
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
```

**Sección destacada advertencia**
> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

**Código**
```
> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.
```

**Sección destacada precaución**
> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

**Código**
```
> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

### :point_right: DESTACAR TEXTO

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


https://docs.github.com/es/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks

https://docs.github.com/es/get-started/accessibility/keyboard-shortcuts

### HERRAMIENTAS

Las herramientas son plataformas que te ayudan a crear algunos elementos en MarkDown mucho más fácil. Te dejo algunas:
- Editor online de HTML: https://onlinehtmleditor.dev/
- Generador de tablas en diferentes formatos: https://www.tablesgenerator.com/

## PLANTILLA 01

<pre> # El título aquí </pre>

<pre> Una imagen como portada </pre>


https://www.aluracursos.com/blog/como-escribir-un-readme-increible-en-tu-github
