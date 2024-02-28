Esercizio di oggi:

# DB First

### nome repo: db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.

# Tabella: AutoUsate

| Campo           | Tipo         | Attributi       |
| --------------- | ------------ | --------------- |
| ID_Auto         | INT          | NOTNULL, UNIQUE |
| Marca           | VARCHAR(50)  | NOTNULL         |
| Modello         | VARCHAR(50)  | NOTNULL         |
| Anno            | INT          | NOTNULL,        |
| Chilometraggio  | INT          | NOTNULL,        |
| Prezzo          | DECIMAL(6,2) | DEFAULT,        |
| Colore          | VARCHAR(20)  | NOTNULL,        |
| Carburante      | VARCHAR(20)  | NOTNULL         |
| Trasmissione    | VARCHAR(20)  | NOTNULL         |
| Stato           | VARCHAR(20)  | NOTNULL         |
| DataInserimento | DATE         | NOTNULL         |
