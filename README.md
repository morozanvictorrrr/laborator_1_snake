# Snake Game

## Descriere
Acest proiect reprezintă o implementare simplă a jocului Snake, un joc clasic în care jucătorul controlează un șarpe care crește în lungime pe măsură ce mănâncă mere.

## Regulile jocului Snake
1. Jucătorul controlează un șarpe care se mișcă într-o direcție.
2. Obiectivul este de a mânca merele pentru a crește în lungime.
3. Jucătorul pierde dacă se lovește de marginea tabloului sau de el însuși.

## Tipuri de date
- **Point**: Reprezintă o poziție pe tabloul de joc, cu coordonate x și y.
- **Apple**: Reprezintă un măr, cu o poziție pe tabloul de joc.
- **Direction**: Enumerează direcțiile posibile de mișcare pentru șarpe (sus, stânga, dreapta, jos).
- **Snake**: Reprezintă șarpele, care are o serie de segmente și poate mânca mere.
- **Board**: Reprezintă tabloul de joc, cu dimensiuni definite.
- **GameEngine**: Gestionați logica jocului, inclusiv generarea merelor și mișcarea șarpelui.
- **Painter**: Responsabil pentru desenarea imaginilor și textului pe tabloul de joc.
