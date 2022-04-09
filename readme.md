-----1-----

Inizio a pensarte che la notazione selettore.selettore in css voglia
indicare

elemento_html.classe_css

però se così fosse, potrei farlo solo con un elemento alla volta

-----2-----

La notazione selettore.selettore.selettore si usa con le classi
e si fa per comprendere tutte le classi di cui dispone un elemento,
per fare in modo che possa essere più facilmente trovato corrrettamente
dal css.

ESEMPIO: questo paragrafo viene trovato con questa regola di stile.
<!--html -->
<p class="in-div color-red size-12">Testo con tante classi</p>
<!--css -->
.in-div.color-red.size-12 {
  background-color:blue ;
}

https://www.youtube.com/watch?v=l1mER1bV0N0&t=926s
-----3-----


il video di web dev simplified spiega cosa significa la notazione 
selector.selector.selector: il non inserire gli spazi permette di indicare
che gli elementi a cui si riferisce possiedono le classi specificate.
Il non inserire gli spazi quindi rappresenta una sorta di operatore and. 
L'elemento possiede la classe 1 e la classe 2 e la classe ..n.