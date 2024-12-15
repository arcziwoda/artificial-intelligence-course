# WSI - Ćwiczenie 1

**Zagadnienie przeszukiwania i podstawowe podejścia do niego**  
_6 października 2023_

---

## Polecenie

1. **Narysować funkcje** \( f(x) \) **i** \( g(x) \).
   - Która z funkcji będzie „łatwiejsza“ do optymalizacji?
2. **Zaimplementować algorytm najszybszego spadku** oraz zastosować go do znalezienia minimum funkcji \( f \) i \( g \).

3. **Zbadać wpływ rozmiaru kroku** dla różnych (losowych) punktów początkowych.
   - Jak często udaje się zlokalizować minimum globalne?

---

### Funkcje

#### Funkcja \( f(x) \)

\[
f(x) = \sin(\pi x) + x^2
\]

#### Funkcja \( g(x) \) (funkcja dwuwymiarowa, \( x_i \) oznacza i-ty element wektora \( x \))

\[
g(x) = 5e^2-4e^{x_1} + x_1^2 + 2e^{x_2} + x_2^2
\]

---

### Gradienty funkcji

\[
\nabla f(x) = \pi \cos(\pi x) + 2x
\]

\[
\nabla g(x) =
\begin{bmatrix}
2(x_1 - 2e) \\
2(x_2 + e)
\end{bmatrix}
\]
