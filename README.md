# Aprendiendo _Markdown_

# Temario Markdown :

1º [Parrafos](#parrafos)

2º [Cursiva y Negrita](#cursiva-y-negrita)

3º [Encabezados](#encabezados)

4º [Enlaces externos](#enlaces-externos)

5º [Enlaces internos](#enlaces-internos)

6º [Enlaces con Imagenes](#enlaces-con-imagenes)

7º [Imagenes en _Markdown_](#imagenes-en-markdown)

8º [Textp pre](#texto-pre)

9º [Division o Hr en _Markdown_](#division-o-hr-en-markdown)

10º [Listas Ordenadas](#listas-ordenadas)

11º [Listas Desordenadas](#listas-desordenadas)

12º [Citaciones](#citaciones)

13º [Tablas](#tablas)

14º [Codigo HTML](#codigo-html)

15º [Comentarios](#comentarios)

---

# Parrafos

Esto es un parrafo 👇 en markdown en el que simplemente hay que escribir y basta.

- Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dicta, quibusdam officia! Dolores explicabo nam aliquid alias? Consequuntur voluptate sapiente, commodi similique eius officia magni recusandae expedita quibusdam, aspernatur enim deleniti?

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Cursiva y negrita

Para Empezar a escribir en cursiva empezamos la palabra o frase o lo que queramos con guion bajo asi:

👇

`_Cursiva_`

y para Negrita seria dos estrellitas antes de la frase o palabrapegado en este caso no separado al igual que cursiva y todo lo contrario de los encabezados

asi:

👇

`**Negrita**`

Aplicando _cursiva_ y **negrita** **_cursiva y negrita_**.

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Encabezados

# Encabezados 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Enlaces externos

👇 Enlaces externos se Escriben asi:

- Entre Corchetes planos (O LOS PARENTESIS PLANOS) el nombre de nuestro link.
- Y justo despues del corchete plano de cierre pegado y sin separacion el parentesis.
- En el parentesis ponemos link o la direccion url eso si con http bla bla bien puesto el link (url).

`[YouTube]`(https://youtube.com/jonmircha)

(👆esto de aqui es esto 👇)

[YouTube](https://youtube.com/jonmircha)

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Enlaces internos

Enlaces internos como las anclas internas de html, Enlaces internos se Escriben asi;

👇

- Entre Corchetes planos [ ] **EL NOMBRE** de nuestro link INTERNO ejemplo 👇Asi:

  `[Aprendiendo _markdown_]`

- Despues (Parentesis) pegado ala derecha del [ corchete al que le hemos dado un nombre anteriormente] sin separacion.

  👇Asi:

  `[Aprendiendo _markdown_ ]()`

- Y en el parentesis, le damos el camino ancla para llegar a ese tema que queremos gracias a la almoadilla.

  👇Asi:

  `[Aprendiendo _markdown_ :](#aprendiendo-markdown)`

  👆Esto es = a este link interno [Aprendiendo _markdown_ :](#aprendiendo-markdown)

  si pulsamos nos llevara arriba del todo como las anclas de html

.

.

Aqui va otro link interno👇

[Otro Encabezado interno de ejemplo hacia cursivas y negrita](#cursiva-y-negrita)

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Enlaces con imagenes

Mas de lo mismo!!

La misma syntaxis corchetes planos **[ ]**, pegados a este... unos parentesis con la url dentro.

`[This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)`

👇Esto se traduce a un link que nos lleva a una foto de leonidas

[This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Imagenes en _Markdown_

Si quisieramos ver la imagen en markdown (Vista previa) en vez de ir al link externo es tan facil como añadir la exclamacion ( **!** ) al comienzo de los corchetes planos!!

👇Asi:

`![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)`

si ponemos atencion ahi esta la exclamacion antes del parentesis plano o corchete plano como quieras llamarlo!

Veamos la foto!!

![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Texto Pre

Hasta ahora hemos visto los **2 ejemplos** en Markdown.

**1. EJEMPLO VISTO EN _MARKDOWN_:**

       Hemos visto el Codigo escrito en el editor:

El **codigo** que el usuario no ve, se ve asi en el editor,

**(Codigo, enlace, funcionalidad...)**

         ![VISTA PREVIA MARKDOWN](/VISTA-PREVIA-MARKDOWN-1.png)

- En la vista previa del usuario, este codigo pasa de esto:

      ` ![VISTA PREVIA MARKDOWN](/VISTA-PREVIA-MARKDOWN-1.png) `

                            a esto 👇:

             (PASA DE CODIGO A SU RESULTADO QUE ES UNA FOTO) 🤦‍♂️😒 No te pongas ha buscar en la foto la foto es el resultado del codigo anterior!

![VISTA PREVIA MARKDOWN](/VISTA-PREVIA-MARKDOWN-1.png)

**2. EJEMPLO VISTO EN _MARKDOWN_:**

       Pero no hemos visto el Codigo escrito en la vista previa:

El **CODIGO PREFORMATEADO** que el usuario ve **EN LA VISTA PREVIA DEL USUARIO SE VE ASI** :

                ![VISTA PREVIA MARKDOWN](/VISTA-PREVIA-MARKDOWN-1.png)

- Para poder escribir un codigo preformateado este debe empeazar con **COMILLA INCLINADA** **`** AL PRINCIPIO DEL CODIGO Y AL FINAL ASI:

           `![VISTA PREVIA MARKDOWN](/VISTA-PREVIA-MARKDOWN-1.png)`

.

.

- **ESPECIAL IMPORTANTE!!**

  - Para mostrar el codigo en bloque tal y cual lo hemos escrito, seria con triple comilla:

  - _inmediatamente despues de las tres comillas le podemos añadir **js** diciendo que es codigo javascript, el editor se encargara de darle lños colores correspondientes!_

        ```js
        function sumar (a, b) {
        return a + b;
        }
        ```    

  - **TAMBIEN PODEMOS IGNORAR DE OTRA MANERA EL CODIGO Y QUE SE MUESTRE DIRECTAMENTE INTERRUMPIENDO LOS CARRACTERES!! 3º

    **EJEMPLO:**


    3. **ASI:**  CON BARRA INVERTIDA ENTRE CARACTERES ESPECIALES
    ```
    \*\*negrita\*\* y \_Cursiva\_
    👇:

    ```
    \*\*negrita\*\*  y  \_Cursiva\_

    
    

```js
function sumar (a, b) {
return a + b;
}
```

**Con esto hemos creado el cuadrado dialogo que vemos ahora mismo desde el inicio sin hacer 4 o 5 tabulaciones!!**

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Division o Hr en _Markdown_

Este es un texto '1'

Y

ESTE ES UN TEXTO 'Z'

    Como TEXTO 1, hace referencia a un numero y no a una letra como lo hace TEXTO Z, significa que es contenido diferente osea una seccion diferente de la que hablamos.

- Entonces lo mas apropiado seria de dividir nuestro contenido con una linea separadora.

  👇Asi:

ESTE ES UN TEXTO '1'

---

y

ESTE ES UN TEXTO 'Z'

---
Esta linea divisoria de aqui 👆 se forma con tres rayas y ya esta! asi: 
👇
```
simplemente asi (👈 despues de escribir este texto, retorno de linea osea enter y ponemos 3 rayitas!)

---

```




.

.

📋[Temario](#temario-markdown)📋

.

---

# Listas Ordenadas

**EN LAS LISTAS ORDENADAS LA MANERA DE CREARLAS ES CON NUMERO Y PUNTO SEGUIDO:**

1.  La forma seria asi:

        Ponemos el numero 1 seguido de un punto:

        asi👇:

            1.
            2.
            3.
            4.

2.  Tambien podriamos hacerlo automatizando markdown

        En vez de utilizar la primera manera podriamos hacerlo con la automatizacion de 'UNOS':

        asi👇:

            1.
            1.
            1.
            1.

            de esta manera puede parecer que no ha cambiado nada pero esto daria resultado al mismo orden del 1 al 4.

**EJEMPLO**

- Esto lo escribiriamos en el editor, y automatizaria solo.
  `1.`

  `1.`

  `1.`

  `1.`

- Esto 👆se ve asi en el edito y en la vista previa va a ser visualmente lo mismo que esto 👇:

  `1.`

  `2.`

  `3.`

  `4.`

       Las dos maneras serian correctas, pero lo aconsejable seria utilizar la automatizada.

  **¡ Y no olvidar de que el texto que precede al punto del uno tiene que estar separado y que no toque el punto el texto de esta forma**

  Buena forma 👇:

  1. Primavera
  2. Verano
  3. Otoño
  4. Invierno

* **mala FORMA** 👇:

  1.Primavera

  2.Verano

  3.Otoño

  4.Invierno

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Listas Desordenadas

- En las **LISTAS DESORDENADAS** tenemos 3 opciones de crearlas:

  1. Con ' + '
  2. Con ' \* '
  3. Con ' - '

- **Ejemplo-1**

  `+` Primavera  
  `+` Verano  
  `+` Otoño  
  `+` Invierno

        la lista va a desembocar en lo mismo en esto 👇:

- Primavera
- Verano
- Otoño
- Invierno

Pongamos CRUZ, PLUS, O ASTERISCO ...

## EN CUANTO A LO VISUAL SERA LO MISMO!

.

.

📋[Temario](#temario-markdown)📋

.

---

# Citaciones

- Para crear una citacion hay 2 formas:

  - La 1º es **Citacion en Linea**:

    - Con esta solo hace falta agregar **'Mayor QUE' ( > )** antes de la frase o lo que sea: 👇Asi:

           > siempre tienes opcion de no tener opinion.
           👇:

    > siempre tienes opcion de no tener opinion.

  - La segunda es **Citacion en Bloque**:

    - Con esta solo hace falta añadir un **'Mayor QUE' ( > )** entre lineas separada es decir: 👇Asi:

          > Todo lo que escuchamos es una opinion, no un hecho.
          >
          > Todo lo que vemos es una perspectiva, no la verdad.
          >
          > Marco Aurelio.
          👇:

    > Todo lo que escuchamos es una opinion, no un hecho.
    >
    > Todo lo que vemos es una perspectiva, no la verdad.
    >
    > Marco Aurelio.

---

.

.

📋[Temario](#temario-markdown)📋

.

---

# Tablas

- **Para crear la tabla No va ha haber mucha explicaion!**

      USAREMOS PIPE! ** ( ESTE PALO QUE SE CREA CON ALT + TECLA Nº1 )
          Asi👇:

          | Nombre | Edad | Correo          |
          | ------ | ---- | --------------- |
          | DSF    | 22   | dsf@gmail.com   |
          | Lucas  | 3    | lucas@gmail.com |
          | Laura  | 5    | Laura@gmail.com |


        ESTO ES ASI👇:

| Nombre | Edad | Correo          |
| ------ | ---- | --------------- |
| DSF    | 22   | dsf@gmail.com   |
| Lucas  | 3    | lucas@gmail.com |
| Laura  | 5    | Laura@gmail.com |

---

.

.

📋[Temario](#temario-markdown)📋

.

---
# Codigo HTML
**_Markdown_ es un lenguage de estructurado al igual que html lo que significa que accepta html como si fuera el mismisimo HTML en persona!**

* POR EJEMPLO!:

```
<form>
  <label for="q">Buscar:</label>
  <input type="search" name="q" id="q">
</form>
  👇:
```

* **IGUAL A=** 

<form>
  <label for="q">Buscar:</label>
  <input type="search" name="q" id="q">
</form>

---

.

.

📋[Temario](#temario-markdown)📋

.

---
# Comentarios
LOS COMENTARIOS SON EXACTAMENTE LO MISMO QUE EN HTML

```
<!- - TEXTO COMMENTARIO - - >

👇 : NO SE VE NADA POR QUE ES UN COMENTARIO SOLO SE VE EN EL EDITOR!! 😂😂😂😂

```

---

.

.

📋[Temario](#temario-markdown)📋

.

---
