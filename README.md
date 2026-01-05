# Aprendizajes del módulo Fundamentos del Desarrollo Web
 **Proyecto 6 Position con CSS **

Se siguio desarrollando la pagina web anterior agregando los nuevos temas vistos, como lo es el banner de cookies, el diseño del navbar y footer.

En este proyecto se implementó: 
  * Uso de `z-index`para posicionar el navbar y el banner de cookies con el resto de los elementos.
  * Uso de `gap` para separar los elementos.
  * Se implemento el `overflow` en en navbar por si el contenido se desborda no se visualice.
  * Se ajusto el tamaño de la letra en el navbar para mejor visualizacion con `font-size` y la trancision con `transition: 0.3s;`, asi como el uso de un logo.
  * Se implemento un banner de cookies con `position: fixed` para que aparezca fijo siempre, asi como el uso de `display: flex` y sus atributos.
  
***
Parte de CSS implementado en este proyecto:

    
    z-index: 1000;
    border-radius: 0 0 10px 10px;
    display: flex;
    gap: 20px;
    overflow: hidden;
    transition: 0.3s;
    display: flex; 
    justify-content: space-between; 
    align-items: center;
    z-index: 2000;
    gap: 12px;

***