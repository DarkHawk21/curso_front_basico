## Emmet

#### ¿Qué es?

Emmet es una herramienta invisible pero muy poderosa que nos permite mejorar drásticamente el flujo de trabajo de HTML y CSS haciendo uso de abreviaciones de palabras y comandos para lograr el autocompletado de etiquetas, reglas de estilo o algún otro elemento incluido en estos dos lenguajes.

#### ¿Cómo se usa?

Emmet trabaja a través de abreviaciones, escribimos una abreviación la cual se expande para completar todo el código que esta representa. Si hemos hecho uso de **CSS** la escritura de Emmet debe sernos muy familiar, pues utiliza la misma estructura que un selector intermedio de ese lenguaje.

Para utilizar la sintaxis de Emmet en VSCode o algún otro editor de código, debemos escribir el comando dentro de nuestro archivo con extensión **html**, seguido de la tecla **tabulador**.

Cada comando escrito tiene una función distinta y se pueden combinar entre sí para lograr realizar acciones complejas y muy complejas.

#### Comandos básicos

1. !
2. html:5
3. .clase
4. #id
5. <etiqueta>
6. <abreviatura> * <cantidad de veces a implementar>
7. <etiqueta>[<atributo de la etiqueta>]
8. +
9. ^
10. $
11. <etiqueta>{<contenido que va dentro de la etiqueta>}

#### Combinación de comandos

Para realizar una combinación compleja o más avanzada, hacemos uso del símbolo **">" (Mayor que)** 

Ejemplo:

- .clase > h1
- .container>.col12>h2+p
- ul.links>li*4>a.link[target=]
- .article.art-$*2>.content>h3+p^.cta>a