# Attraversare la strada

- Usciamo dal portone di casa
    - prendo le chiavi
    - apro la porta
    - esco di casa 
    - chiudo a chiave la porta
    - inizio a camminare fino al marciapiede
    - cerchiamo le strisce pedonali più vicine

- Arriviamo al ciglio del marciapiede

    - IF è presente un semaforo pedonale
        - verifico lo stato del semaforo
            - IF è verde
                - attraverso
            - ELSE 
                - verifico lo stato del semaforo

            - IF è giallo
                - IF è appena scattato
                    - attraversiamo correndo
                - ELSE mi fermo finchè non è rosso
            - ELSE 
                - verifico lo stato del semaforo

            - IF è rosso
                - prenotiamo il semaforo
                - aspettiamo diventi verde
            - ELSE 
                - verifico lo stato del semaforo

    - ELSE non è presente un semaforo pedonale
        - controllo il senso di marcia
            - IF è senso unico
                - guardo solo dal lato di provenienza delle auto
            - ELSE
                - guardo da entrambi i lati

        - controllo la presenza di auto in arrivo
            - IF arrivano auto
                - resto fermo
            - ELSE 
                - attraverso


- Attraversiamo
    - comincio a camminare verso il lato opposto della strada
        - IF si presenta un pericolo (tipo sirene o guidatori distratti)
            - IF sei all'inizio delle strisce pedonali
                - torni indietro
            - ELSE 
                - corriamo verso il lato opposto
        - ELSE
            - raggiungo il lato opposto della strada

- Salgo sul marciapiede
    - mi dirigo verso la destinazione desiderata