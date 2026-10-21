# Adriaque
flowchart TD
    Inicio([Inicio]) --> Entrada[/Pedir número N/]
    Entrada --> Decision{¿N % 2 == 0?}
    Decision -- Sí --> EsPar[/Imprimir 'Es Par'/]
    Decision -- No --> EsImpar[/Imprimir 'Es Impar'/]
    EsPar --> Fin([Fin])
    EsImpar --> Fin
