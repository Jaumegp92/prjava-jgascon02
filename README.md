# prjava-jgascon02

git checkout -b branca00 (crear i situar-se a una nova branca)

git checkout main (tornar a una altra branca)

git merge branca00 (afegir el codi de la branca00 que no apareix a la branca main)

git push -u (pujar arxius al repositori remot)

El contingut afegit a l'arxiu de la branca00 no apareix al Visual Studio Code si estàs situat a la branca main, 
perquè aquest contingut no existeix a l'arxiu d'aquesta branca.

Si es fa un merge només s'actualitza la branca main, ja que afegeix noves línies de codi. 
La branca00 no s'actualitza perquè no es produeix cap canvi en aquesta branca.
