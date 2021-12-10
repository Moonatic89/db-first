# Concessionaria Pino

## Auto

- id | BIGINT - PRIMARY KEY, AUTO INCREMENT, UNIQUE, NOT NULL
- marca | VARCHAR(20) - NOT NULL
- modello | VARCHAR(10) - NOT NULL
- immagine | VARCHAR(255) - NULL 
- generazione | VARCHAR(20) - NULL
- serie | VARCHAR(20) - NULL
- modifiche | VARCHAR(20) - NULL
- condizioni | VARCHAR(10) - NULL
- usura | (KM) MEDIUMINT - NULL
- cambio | VARCHAR(10) - NULL
- alimentazione | VARCHAR(10) - NULL
- consumi | VARCHAR(15) - NULL
- prezzo | DECIMAL (8,2) - NULL
- sconto | TINYINT - NULL
- disponibilità | TINYINT - DEFAULT(1)
- quantità | TINYINT - NOT NULL
- ecoincentivo | INT - NULL
