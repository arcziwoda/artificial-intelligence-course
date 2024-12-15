# WSI - Ćwiczenie 3

**Dwuosobowe gry deterministyczne**  
_6 listopada 2023_

---

## 2. Polecenie

### Cel ćwiczenia

Celem ćwiczenia jest implementacja algorytmu **minimax z obcinaniem α-β**.

- Algorytm powinien zwracać losowy ruch spośród tych o tej samej jakości.

### Zadania

1. **Implementacja algorytmu minimax z obcinaniem α-β**.
2. Wykorzystanie algorytmu do porównania skuteczności dla różnych **głębokości przeszukiwania** na potrzeby gry o następujących zasadach:
   - **Gra w żetony**:
     - Na początku gry dany jest zbiór \( N \) identycznych żetonów.
     - Dwóch graczy wykonuje ruchy na zmianę.
     - Podczas swojej tury gracz usuwa od **1 do \( K \)** żetonów.
     - Przegrywa gracz, który **zabierze ostatni żeton**.

### Eksperymenty

- Ustalenie parametrów:
  - \( K = 3 \).
  - \( N \) losowane z zakresu \( [8, 20] \) (z rozkładem jednostajnym).
- Porównanie skuteczności algorytmu dla różnych głębokości przeszukiwania.
