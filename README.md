# Avtomate 1

Pregledovalnik (scanner) predstavlja vmesnik med izvornim programom in razpoznavalnikom. Njegova naloga je, da vrne razpoznavalniku terminalne simbole. Njegova naloga je tudi, da izloči prazna mesta ter komentarje.

Pregledovalnik obravnava vhodno datoteko kot niz znakov, ki jih nato sestavlja v terminalne simbole. Za opis terminalnih simbolov uporabljamo končne avtomate, te pa najlažje implementiramo s tabelo.

Osnovni leksikalni simboli:

```
float [0-9]+(.[0-9]+)?
variable [a-zA-Z]+[0-9]*
plus \+
minus -
times \*
divide /
pow ^
lparen \(
rparen \)
```

Leksikalni analizator implementirajte v poljubnem jeziku.
