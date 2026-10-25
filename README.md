# Five-Card Poker Hand Comparison

A small Python simulation that deals two five-card hands from a standard deck, identifies their combinations and compares their ranks.

## Run

Python 3.8 or newer; only the standard library is required.

```bash
python pocker.py
```

The program prints both hands, their highest-ranked combinations and the comparison result.

## Implementation

[Source](pocker.py) separates cards, the deck, hands and combination classes. The comparison logic handles categories from high card and pairs through straights, flushes and higher-ranked combinations.

The focus is combinatorial representation and ordering: how a hand's category and relevant card values determine its rank. The current program deals and compares hands automatically; it has no betting strategy or learned decision policy.

This is an early algorithmic programming exercise. My subsequent work on uncertainty and statistical modelling is collected in [Computational Statistics](https://github.com/jeck5iv/pricmatstat) and [Monte Carlo coursework](https://github.com/jeck5iv/Coursework).
