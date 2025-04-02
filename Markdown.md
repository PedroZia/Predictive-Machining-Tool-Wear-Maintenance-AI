```mermaid
    graph LR
    A[Início] --> B{Decisão}
    B -->|Sim| C[Processo 1]
    B -->|Não| D[Processo 2]
    C --> E[Fim]
    D --> E[Fim]
    C[Sensor] -->
