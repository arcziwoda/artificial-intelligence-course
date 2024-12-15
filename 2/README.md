# WSI - Ćwiczenie 2

**Algorytmy ewolucyjne i genetyczne**  
_21 października 2023_

---

## 2. Polecenie

### Cel ćwiczenia

Celem ćwiczenia jest implementacja **algorytmu ewolucyjnego** z następującymi komponentami:

- **Selekcja turniejowa** (k = 2).
- **Krzyżowanie jednopunktowe**.
- **Mutacja gaussowska**.
- **Sukcesja generacyjna**.

Następnie należy wykorzystać implementację do znalezienia rozwiązania dającego minimum dla problemu opisanego sumą \( f_1 \) i \( f_2 \), gdzie:

#### Funkcja \( f_1(x_1, y_1) \)

\[
f_1(x_1, y_1) = (x_1^2 + y_1 - 11)^2 + (x_1 + y_1^2 - 7)^2
\]

#### Funkcja \( f_2(x_2, y_2) \)

\[
f_2(x_2, y_2) = 2x_2^2 + 1.05x_2^4 + \frac{x_2^6}{6} + x_2y_2 + y_2^2
\]

Obie funkcje definiowane są dla dziedziny:  
\[
D = [-5, 5] \times [-5, 5].
\]

---

### Zadania do wykonania

1. Znaleźć zestaw hiperparametrów, który daje stosunkowo dobry wynik.

2. Zbadać wpływ następujących czynników na współrzędne znalezionych minimów dla funkcji \( f_1 \):

   - **Dystrybucji populacji początkowej**:
     - Jednorodny rozkład po całym obszarze.
     - Rozkład normalny wokół punktu \([x_1 = -0.3, y_1 = -0.9]\) (dla \( f_1 \)) oraz dowolnie przyjęty punkt dla \( f_2 \).
   - **Prawdopodobieństwa mutacji** w rozsądnym przedziale wartości.
   - **Prawdopodobieństwa krzyżowania** dla wartości z przedziału \( [0.8, 0.95] \).

3. Zwizualizować za pomocą wykresów dystrybucję populacji na poszczególnych etapach optymalizacji z podziałem na odpowiednie funkcje.
