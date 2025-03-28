# Attraversare la strada

Semafori, rotonde e precedenze… al test per la patente, la domanda sugli incroci manda sempre un po’ in confusione! Per stavolta ci concentriamo solamente sugli step da fare per attraversare la strada, sapendo che ogni passo deve essere ben misurato altrimenti potrebbe costarci caro!

### Elementi a disposizione

    - Strisce pedonali
    - Semaforo
    - Corsia 1
    - Corsia 2
    - Veicoli

### Algoritmo

    - SE ( luce del semaforo verde AND, NOT veicoli su Corsia1 AND, NOT veicoli su Corsia2 )
        - ALLORA Attraversa sulle strisce pedonali

# Caricare una foto su Instagram

Durante le vacanze ho fatto mille mila foto, ora come faccio a scegliere quella giusta da caricare su Instagram? I paesaggi mozzafiato che ho visitato non ne avrebbero bisogno, però cercherò il filtro giusto per migliorare la luce e rendere più vividi i colori, in modo che le foto rendano giustizia alla bellezza della natura

### Elementi a disposizione

    - Cellulare
    - Fotografie
    - Filtri
    - Instagram

### Algoritmo

    - FINCHE' ( Foto ok ) Loop 1
        - Apri foto
        - FINCHE' (filtro ok) Loop 2
            - Aggiungi Nuovo filtro
            - SE (Filtro = ok)
                - Aggiungi foto a preferiti | Esce dal loop 2
            ALTRIMENTI
                - Cambia Filtro
        - SE (Foto ok)
            - Pubblica su INSTAGRAM | Esce dal loop 1
