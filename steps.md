# Ordinare una pizza
Dopo una lunga giornata passata al pc, ho proprio voglia di concedermi una bella pizza succulenta! Sì, ma
quale? Fammi dare un occhio al listino… Va beh, è inutile, tanto alla fine ordino sempre la stessa: una
classica prosciutto e funghi. La pizza arriva ancora fumante, chissà se riuscirò a mangiarla tutta!
Di sicuro se ne avanzo una fetta devo ricordarmi di metterla in frigo, non come l’ultima volta!
<br>
<hr>
<br>

- 01 **SE NON** ho voglia della solita pizza
    - 02 leggo il menù
    - 03 scelgo la nuova pizza
    - 04 **SE** sono già al telefono
        - 05 vado a row **10**; _se non è disponibile la pizza che ho scelto_    
- 06 Chiamo
- 07 **SE** non mi risponono
    - 08 Aspetto
    - 09 vado al row **06**; _Chiamo_
- 10 **SE NON** è disponibile la pizza che ho scelto:
    - 11 vado a row **02**; _leggo il menù_
- 12 Ordino
- 13 Pago
- 14 Mangio una fetta di pizza
- 16 **SE NON** ci sono altre fette di pizza
    - 17 **FINE**
- 18 **Altrimenti**
    - 19 **SE** sono sazio
        - 20 metto la pizza nel frigo
        - 21 **FINE**
    - 22 **Altrimenti** torno a row: **13**; _mangio una fetta di pizza_