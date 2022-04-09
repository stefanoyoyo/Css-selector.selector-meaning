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
