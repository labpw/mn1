 
### 1. **Gradient w kierunku osi \( x \) (poziomy)**

Gradient w kierunku osi \( x \) opisuje, jak funkcja zmienia się, gdy poruszamy się w poziomie (wzdłuż osi \( x \)). Obliczamy go, biorąc różnicę między wartością funkcji w sąsiednich punktach w kierunku poziomym.

#### Wzór:
\[
\frac{\partial F}{\partial x}(x, y) \approx \frac{F(x+1, y) - F(x-1, y)}{2h}
\]

- **\( F(x+1, y) \)** to wartość funkcji w punkcie po prawej stronie punktu \( (x, y) \).
- **\( F(x-1, y) \)** to wartość funkcji w punkcie po lewej stronie punktu \( (x, y) \).
- **\( h \)** to odległość między punktami w siatce (zwykle \( h = 1 \), ale może być dowolna).

 
---

### 2. **Gradient w kierunku osi \( y \) (pionowy)**

Gradient w kierunku osi \( y \) opisuje, jak funkcja zmienia się, gdy poruszamy się w pionie (wzdłuż osi \( y \)).

#### Wzór:
\[
\frac{\partial F}{\partial y}(x, y) \approx \frac{F(x, y+1) - F(x, y-1)}{2h}
\]

- **\( F(x, y+1) \)** to wartość funkcji w punkcie powyżej \( (x, y) \).
- **\( F(x, y-1) \)** to wartość funkcji w punkcie poniżej \( (x, y) \).
- **\( h \)** to odległość między punktami w siatce.
 
---

### 3. **Gradient w kierunku przekątnej \( (+1, +1) \) (ukośny w prawo do góry)**

Gradient w tym przypadku opisuje, jak funkcja zmienia się, gdy poruszamy się w kierunku przekątnej (od lewej dolnej strony do prawej górnej).

#### Wzór:
\[
\frac{\partial F}{\partial (x,y)}(x+1, y+1) \approx \frac{F(x+1, y+1) - F(x, y)}{\sqrt{2} \cdot h}
\]

- **\( F(x+1, y+1) \)** to wartość funkcji w punkcie na przekątnej w prawo i w górę.
- **\( F(x, y) \)** to wartość funkcji w punkcie początkowym \( (x, y) \).
- **\( \sqrt{2} \)** to czynnik, ponieważ odległość między dwoma punktami na przekątnej w siatce jest większa o \( \sqrt{2} \) w porównaniu do odległości w poziomie lub pionie.
 
 