# Adriaque
# Práctica de Diagramas Mermaid

## 1. Diagrama de Flujo (Par o Impar)
Algoritmo que pide un número y determina si es par o impar.

```mermaid
flowchart TD
    A[Inicio] --> B[/Leer número N/]
    B --> C{N % 2 == 0?}
    C -- Sí --> D[Imprimir: Es Par]
    C -- No --> E[Imprimir: Es Impar]
    D --> F[Fin]
    E --> F
