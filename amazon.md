# Comprare qualcosa su Amazon

- Prodotti Amazon
- Tempistiche
- Budget
- Preferenze

## Algoritmo

- FINCHE' NON trovo un prodotto d'interesse
  - Sfoglio prodotti
  - SE trovo un prodotto d'interesse assegno un valore 1
    - SE Il prodotto ha consegna Prime minore o uguale ad un giorno
      - assegno un valore 1
    - SE Il costo del prodotto è minore o uguale al budget
      - assegno un valore 1
  - SE trovo un prodotto di valore 3 lo aggiungo al carrello
  - Vado nella pagina del pagamento
    - SE posso pagare con PayPal
      - Acquisto il prodotto
    - ALTRIMENTI pago con carta
