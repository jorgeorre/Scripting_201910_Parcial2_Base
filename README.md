# Scripting_201910_Parcial2_Base

Jorge Andrés Orrego 000287268

Para la implemtanción de los proyectiles usaria en este caso el patrón de diseño Pool, ya que me permite tener un numero de objetos en escena y reutlizarlos, sin necesidad de estar instanciando uno nuevo ni dustruyendolos.

Para la implementación de los AI diferentes, 3 Pool para cada AI me parece que tambien puede ser la mejor opción por lo de que esto tambien me permite controlar cuantos AI de ese tipo estan en escena que cuando uno muera otro de el mismo tipo lo reemplace, esto optmimiza de buena manera el juego, aunque algunos dirian que un Factory es la mejor opcion por lo que tenemos AI's diferentes a mi modo de vista en terminos de intanciación y eliminación los Pools son mejores. Ademas de que puedo decirle al pool por codigo cuando volver a poner en escena las instancias de AI (cuando ya no quede ninguna InGame).
