# 📘 GUÍA INTEGRAL DE AUTOESTUDIO Y ENSAYO FORMATIVO DE MATEMÁTICA
## II MEDIO · COBERTURA CURRICULAR BASES CURRICULARES MINEDUC (MA2M OA01 – OA12)
> **Instrucciones para GitHub Pages:** Guarda este archivo exactamente con el nombre `index.md` en la raíz de tu repositorio y activa GitHub Pages en la pestaña *Settings > Pages*. El documento se desplegará automáticamente como un sitio web interactivo con elementos desplegables y fórmulas formateadas.

---

## 🗺️ MATRIZ DE ALINEACIÓN CURRICULAR

| Eje Temático | Cobertura OA Mineduc | Contenidos Evaluados | Cantidad de Preguntas |
| :--- | :--- | :--- | :--- |
| **1. Números** | MA2M OA01, OA02 | Raíces n-ésimas, propiedades de radicales, potencias con exponente racional, definición y propiedades de logaritmos. | Preguntas 1 a 5, 21 a 24 |
| **2. Álgebra y Funciones** | MA2M OA03, OA04, OA05 | Función cuadrática (canónica/general, vértice, eje de simetría), ecuaciones cuadráticas, función inversa y modelo exponencial porcentual. | Preguntas 6 a 12, 25 a 31 |
| **3. Geometría y Trigonometría** | MA2M OA07, OA08, OA09 | Área y volumen de la esfera, razones trigonométricas en $\triangle$ rectángulo ($\operatorname{sen}, \cos, \tan$), representación y proyección de vectores. | Preguntas 13 a 16, 32 a 35 |
| **4. Probabilidades y Estadística** | MA2M OA10, OA11, OA12 | Variables aleatorias discretas, función de probabilidad, regla de Laplace, principio multiplicativo, permutaciones y combinaciones $C(n,k)$. | Preguntas 17 a 20, 36 a 39 |

---

# MÓDULO I: GUÍA CONCEPTUAL Y ESTRATÉGICA

### UNIDAD 1: Números Reales (Raíces, Potencias y Logaritmos)

* **Descomposición de Radicales:** Para $a \ge 0, b \ge 0$: $\sqrt{a^2 \cdot b} = a\sqrt{b}$.
  * *Estrategia:* Descompón en producto usando cuadrados perfectos ($1, 4, 9, 16, 25, 36, 49, 64, 81, 100$). Ejemplo: $\sqrt{72} = \sqrt{36 \cdot 2} = 6\sqrt{2}$.
* **Relación Exponente Racional y Raíz:** $a^{\frac{m}{n}} = \sqrt[n]{a^m}$.
* **Definición de Logaritmo:** $\log_b(a) = c \iff b^c = a$, con $b > 0, b \neq 1$ y $a > 0$.
* **Propiedades Operatorias:**
  * $\log_b(M \cdot N) = \log_b M + \log_b N$
  * $\log_b\left(\frac{M}{N}\right) = \log_b M - \log_b N$
  * $\log_b(M^k) = k \cdot \log_b M$

> 💡 **Atajo de Cálculo / Comparación de Radicales:**
> Para ordenar expresiones irracionales como $2$, $\sqrt{5}$ y $\sqrt{8}$, eleva todos los términos al cuadrado:
> $2^2 = 4$, $(\sqrt{5})^2 = 5$, $(\sqrt{8})^2 = 8$. Como $4 < 5 < 8$, el orden es $2 < \sqrt{5} < \sqrt{8}$.

> ⚠️ **Alerta de Error Frecuente:** La raíz de una suma **NO** es la suma de las raíces: $\sqrt{a+b} \neq \sqrt{a} + \sqrt{b}$.

---

### UNIDAD 2: Función Cuadrática y Ecuaciones de Segundo Grado

* **Forma Canónica:** $f(x) = a(x - h)^2 + k$. Vértice en $(h, k)$ y eje de simetría en la recta vertical $x = h$.
* **Forma General:** $f(x) = ax^2 + bx + c$. Eje de simetría: $x = -\frac{b}{2a}$.
* **Corte con los Ejes:**
  * Eje $Y$: $(0, c)$.
  * Eje $X$: Puntos $(x, 0)$ obtenidos resolviendo $ax^2 + bx + c = 0$.

> 💡 **Atajo de Signos en Forma Canónica:** En $f(x) = (x - 2)^2 - 3$, invierte el signo dentro del paréntesis ($h = 2$) y conserva el exterior ($k = -3$). Vértice: $(2, -3)$.

---

### UNIDAD 3: Función Inversa

* **Procedimiento:**
  1. Escribir $y = f(x)$.
  2. Intercambiar variables: $x \leftrightarrow y$.
  3. Despejar $y$.
* **Propiedad Clave:** Si $f(a) = b$, entonces $f^{-1}(b) = a$.

---

### UNIDAD 4: Modelos de Crecimiento y Decrecimiento Porcentual

* **Factor Multiplicador:**
  * Aumento del $r\% \implies \text{Factor} = 1 + \frac{r}{100}$
  * Disminución del $r\% \implies \text{Factor} = 1 - \frac{r}{100}$
* **Modelo Exponencial:** $C(t) = C_0 \cdot (\text{Factor})^t$.
* **Diferencia entre periodos consecutivos:** $f(t+1) - f(t) = r \cdot f(t)$.

---

### UNIDAD 5: Geometría y Trigonometría

* **Esfera:** Área Superficial $A = 4\pi r^2$ | Volumen $V = \frac{4}{3}\pi r^3$.
* **Razones Trigonométricas:**
  $$\operatorname{sen}(\alpha) = \frac{\text{Cateto Opuesto}}{\text{Hipotenusa}} \quad | \quad \cos(\alpha) = \frac{\text{Cateto Adyacente}}{\text{Hipotenusa}} \quad | \quad \tan(\alpha) = \frac{\text{Cateto Opuesto}}{\text{Cateto Adyacente}}$$
* **Proyección Vectorial:** Para $\vec{u}$ con módulo $u$ y ángulo $\theta$ respecto al eje $X$: Proyección en $Y = (0, u \operatorname{sen} \theta)$.

---

### UNIDAD 6: Probabilidad, Variables Aleatorias y Combinatoria

* **Variable Aleatoria Discreta:** Función que asigna un valor numérico real a cada resultado de un experimento.
* **Laplace:** $P(A) = \frac{\text{Casos Favorables}}{\text{Casos Totales}}$.
* **Técnicas de Conteo:**
  * **Combinación** (el orden NO importa): $C(n, k) = \frac{n!}{k!(n-k)!}$
  * **Permutación** (el orden SÍ importa): $P_n = n!$

---

## 💻 HERRAMIENTAS COMPUTACIONALES DE APOYO (Python / Google Colab)

Los siguientes scripts permiten simular y comprobar resultados directamente en un entorno ejecutable:

```python
# Script 1: Simulación del Volumen y Área de una Esfera
import math

def evaluar_esfera(radio, pi_aprox=None):
    pi = pi_aprox if pi_aprox else math.pi
    area = 4 * pi * (radio ** 2)
    volumen = (4 / 3) * pi * (radio ** 3)
    return round(area, 2), round(volumen, 2)

# Ejemplo para radio = 3 cm y pi real
area, vol = evaluar_esfera(3)
print(f"Radio 3 cm -> Área: {area} cm², Volumen: {vol} cm³")
```

```python
# Script 2: Cálculo de Combinatorias C(n, k)
import math

def combinatoria(n, k):
    return math.comb(n, k)

# Ejemplo: Seleccionar 3 estudiantes de 7
print(f"C(7, 3) = {combinatoria(7, 3)} formas distintas")
```

---

# MÓDULO II: ENSAYO DE PRÁCTICA DIAGNÓSTICA (39 PREGUNTAS)

**Instrucciones:** Lee atentamente cada ítem y selecciona la alternativa correcta. En las preguntas con recuadro, registra tu procedimiento. Tiempo recomendado: 80–90 minutos.

1. ¿Cuál es el orden creciente correcto de $2$, $\sqrt{5}$ y $\sqrt{8}$?
   - A) $\sqrt{5} < 2 < \sqrt{8}$
   - B) $2 < \sqrt{5} < \sqrt{8}$
   - C) $2 < \sqrt{8} < \sqrt{5}$
   - D) $\sqrt{8} < \sqrt{5} < 2$

2. ¿A qué expresión equivale $\sqrt{72}$?
   - A) $6\sqrt{2}$
   - B) $8\sqrt{2}$
   - C) $3\sqrt{8}$
   - D) $12\sqrt{2}$

3. ¿Qué potencia equivale a la raíz cúbica de $5^2$?
   - A) $5^{3/2}$
   - B) $5^{2/3}$
   - C) $5^{1/6}$
   - D) $5^{-2/3}$

4. ¿Cuál es el valor de $\log_2(16)$?
   - A) $2$
   - B) $3$
   - C) $4$
   - D) $8$

5. ¿Cuál es el valor de $\log_9\left(\frac{1}{3}\right)$?
   - A) $-2$
   - B) $-1$
   - C) $-\frac{1}{2}$
   - D) $\frac{1}{2}$

6. La función $f(x) = (x-2)^2 - 3$ tiene vértice en:
   - A) $(-2, -3)$
   - B) $(2, -3)$
   - C) $(2, 3)$
   - D) $(-2, 3)$

7. ¿Cuál es el eje de simetría de $f(x) = (x+1)^2 - 4$?
   - A) $x = -4$
   - B) $x = -1$
   - C) $x = 1$
   - D) $y = -4$

8. Un marco rectangular tiene dimensiones exteriores de $20\text{ cm}$ por $12\text{ cm}$ y un borde uniforme de $x\text{ cm}$. ¿Qué expresión representa el área interior?
   - A) $240 - 32x + 4x^2$
   - B) $240 - 64x + 4x^2$
   - C) $240 - 32x - 4x^2$
   - D) $240 - 64x - 4x^2$

   > **Procedimiento / Justificación:**
   > _________________________________________________________________________________________

9. ¿Cuáles son las soluciones de $5x^2 = 45$?
   - A) $3$ y $-3$
   - B) $9$ y $-9$
   - C) $\sqrt{5}$ y $-\sqrt{5}$
   - D) Solo $3$

10. Si $h(x) = \sqrt{5x}$, con $x \ge 0$, ¿cuál es su función inversa $h^{-1}(x)$?
    - A) $h^{-1}(x) = 5x^2$
    - B) $h^{-1}(x) = \frac{x^2}{5}$
    - C) $h^{-1}(x) = \sqrt{\frac{x}{5}}$
    - D) $h^{-1}(x) = \frac{5}{x^2}$

11. Si $f^{-1}(4) = 10$, ¿qué igualdad necesariamente se cumple?
    - A) $f(4) = 10$
    - B) $f(10) = 4$
    - C) $f^{-1}(10) = 4$
    - D) $f(4) = 4$

12. Una cantidad inicial de $100$ unidades disminuye $20\%$ en cada periodo. ¿Qué expresión modela la cantidad después de $t$ periodos?
    - A) $100 \cdot (1,2)^t$
    - B) $100 \cdot (0,8)^t$
    - C) $100 - 20t$
    - D) $80t$

13. ¿Cuál es el volumen de una esfera de radio $3\text{ cm}$?
    - A) $12\pi\text{ cm}^3$
    - B) $27\pi\text{ cm}^3$
    - C) $36\pi\text{ cm}^3$
    - D) $108\pi\text{ cm}^3$

14. En un triángulo rectángulo, respecto de $\alpha$, el cateto adyacente mide $8\text{ cm}$ y $\tan(\alpha) = \frac{3}{4}$. ¿Cuánto mide el cateto opuesto?
    - A) $4\text{ cm}$
    - B) $6\text{ cm}$
    - C) $8\text{ cm}$
    - D) $10\text{ cm}$

    > **Procedimiento / Justificación:**
    > _________________________________________________________________________________________

15. En un triángulo rectángulo, el cateto opuesto a $\alpha$ mide $5$ y la hipotenusa mide $13$. ¿Cuánto vale $\operatorname{sen}(\alpha)$?
    - A) $\frac{5}{13}$
    - B) $\frac{12}{13}$
    - C) $\frac{5}{12}$
    - D) $\frac{13}{5}$

16. Un vector de módulo $10$ forma un ángulo de $30^\circ$ con el eje $X$ positivo. ¿Cuál es su proyección vectorial sobre el eje $Y$?
    - A) $(10 \cos 30^\circ, 0)$
    - B) $(0, 10 \operatorname{sen} 30^\circ)$
    - C) $(0, 10 \cos 30^\circ)$
    - D) $(10 \operatorname{sen} 30^\circ, 0)$

    > **Procedimiento / Justificación:**
    > _________________________________________________________________________________________

17. Se extrae una ficha de cada una de tres bolsas. Si $X$ es la cantidad de fichas rojas obtenidas, ¿cuál descripción corresponde a una variable aleatoria?
    - A) El color de la bolsa
    - B) La cantidad de fichas rojas obtenidas
    - C) El número de bolsas
    - D) La cantidad de fichas que había antes

18. Una caja contiene cuatro tarjetas equiprobables numeradas 1, 2, 3 y 4. Si $X$ es el número obtenido, ¿cuál es $P(X=2)$?
    - A) $\frac{1}{2}$
    - B) $\frac{1}{3}$
    - C) $\frac{1}{4}$
    - D) $\frac{3}{4}$

19. ¿De cuántas maneras se pueden seleccionar 3 estudiantes de un grupo de 7, sin importar el orden?
    - A) $21$
    - B) $28$
    - C) $35$
    - D) $42$

20. Cuatro libros distintos se ordenan al azar en un estante. Dos libros específicos deben quedar en los extremos. ¿Cuál es la probabilidad de que esto ocurra?
    - A) $\frac{1}{6}$
    - B) $\frac{1}{4}$
    - C) $\frac{1}{3}$
    - D) $\frac{1}{2}$

21. ¿Cuál es el resultado de $\sqrt{12} \cdot \sqrt{3}$?
    - A) $3$
    - B) $6$
    - C) $6\sqrt{3}$
    - D) $12$

22. ¿Cuál es el valor de $\log_2(\sqrt{8}) + \log_2(4)$?
    - A) $\frac{5}{2}$
    - B) $3$
    - C) $\frac{7}{2}$
    - D) $4$

23. ¿Cuál es la simplificación de $\sqrt{75} - \sqrt{12}$?
    - A) $\sqrt{3}$
    - B) $2\sqrt{3}$
    - C) $3\sqrt{3}$
    - D) $7\sqrt{3}$

24. Si $\text{pH} = -\log(c)$ y $c = 2 \cdot 10^{-4}$, ¿qué expresión representa el $\text{pH}$?
    - A) $4 + \log 2$
    - B) $4 - \log 2$
    - C) $-4 - \log 2$
    - D) $-4 + \log 2$

25. La función $f(x) = (x-3)^2 + 2$ tiene como eje de simetría la recta:
    - A) $x = -3$
    - B) $x = 2$
    - C) $x = 3$
    - D) $y = 2$

26. ¿Cuál función cuadrática cumple $f(0) = -3$, $f(1) = -4$ y $f(3) = 0$?
    - A) $x^2 - 2x - 3$
    - B) $x^2 + 2x - 3$
    - C) $x^2 - 4x - 3$
    - D) $x^2 - 3$

27. Si $f(x) = 2x^2 - 3x + 5$, ¿dónde intersecta su gráfica al eje $Y$?
    - A) $(0, -3)$
    - B) $(0, 2)$
    - C) $(0, 5)$
    - D) $(5, 0)$

28. ¿Cuál es una solución de $x^2 - 5x + 6 = 0$?
    - A) $1$
    - B) $2$
    - C) $4$
    - D) $6$

29. Sea $g(x) = 5x - 10$. ¿Cuál es el valor de $g^{-1}(15)$?
    - A) $1$
    - B) $3$
    - C) $5$
    - D) $25$

    > **Procedimiento / Justificación:**
    > _________________________________________________________________________________________

30. Una cuenta aumenta un $6\%$ cada año. ¿Qué expresión representa el aumento del capital entre los años $t$ y $t+1$?
    - A) $f(t+1) - f(t) = 0,06 \cdot f(t)$
    - B) $f(t+1) - f(t) = 0,6 \cdot f(t)$
    - C) $f(t+1) - f(t) = 1,06 \cdot f(t)$
    - D) $f(t+1) - f(t) = 6 \cdot f(t)$

31. Una producción es de $1.500$ unidades en el primer mes y aumenta $10\%$ mensual. ¿Cuánto produce en el tercer mes?
    - A) $1.650$
    - B) $1.800$
    - C) $1.815$
    - D) $1.950$

32. ¿Cuál es el área superficial de una esfera de radio $5\text{ cm}$?
    - A) $25\pi\text{ cm}^2$
    - B) $50\pi\text{ cm}^2$
    - C) $100\pi\text{ cm}^2$
    - D) $125\pi\text{ cm}^2$

33. Un compartimento dispone de $20\text{ cm}^3$. Se introducen esferas de radio $1\text{ cm}$. Usando $\pi \approx 3$, ¿cuántas esferas completas caben como máximo si se considera solo el volumen estricto?
    - A) $4$
    - B) $5$
    - C) $6$
    - D) $8$

    > **Procedimiento / Justificación:**
    > _________________________________________________________________________________________

34. En un triángulo rectángulo, respecto de $\alpha$, el cateto adyacente mide $9$ y la hipotenusa $15$. ¿Cuál es $\cos(\alpha)$?
    - A) $\frac{3}{5}$
    - B) $\frac{4}{5}$
    - C) $\frac{5}{3}$
    - D) $\frac{5}{4}$

35. Una rampa forma un ángulo $\alpha$ con el suelo. Si $\tan(\alpha) \approx 0,6$ y el avance horizontal es $2.400\text{ m}$, ¿cuál es el ascenso vertical aproximado?
    - A) $400\text{ m}$
    - B) $1.000\text{ m}$
    - C) $1.440\text{ m}$
    - D) $4.000\text{ m}$

    > **Procedimiento / Justificación:**
    > _________________________________________________________________________________________

36. Se extraen dos letras de la palabra SOL, sin reposición. Si $X$ es la cantidad de consonantes extraídas, ¿qué valores puede tomar $X$?
    - A) $\{0\}$
    - B) $\{1\}$
    - C) $\{0, 1, 2\}$
    - D) $\{1, 2, 3\}$

37. Una variable aleatoria toma los valores 1, 2 y 3 con probabilidades $\frac{1}{2}$, $\frac{1}{3}$ y $\frac{1}{6}$ respectivamente. ¿Cuál es $P(X \ge 2)$?
    - A) $\frac{1}{6}$
    - B) $\frac{1}{3}$
    - C) $\frac{1}{2}$
    - D) $\frac{2}{3}$

38. ¿Cuántos números distintos de cuatro cifras se forman ordenando una vez cada una de las tarjetas 1, 2, 3 y 4?
    - A) $12$
    - B) $16$
    - C) $24$
    - D) $256$

39. Se eligen 2 estudiantes de un grupo de 5. Tres están especialmente interesados en el área técnica. ¿Cuál es la probabilidad de que al menos uno de los tres interesados sea seleccionado?
    - A) $\frac{3}{10}$
    - B) $\frac{6}{10}$
    - C) $\frac{9}{10}$
    - D) $1$

---

# MÓDULO III: SOLUCIONARIO INTERACTIVO CON RETROALIMENTACIÓN DESPLEGABLE

Haz clic en **"Ver solución y retroalimentación"** en cada ítem para desplegar la respuesta correcta, el procedimiento paso a paso y el análisis de errores de los distractores.

<details>
<summary><b>Pregunta 1 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Elevemos cada número al cuadrado para comparar sus valores exactos sin estimar decimales:
  * $2^2 = 4$
  * $(\sqrt{5})^2 = 5$
  * $(\sqrt{8})^2 = 8$
  Como $4 < 5 < 8$, la relación entre las raíces es $2 < \sqrt{5} < \sqrt{8}$.
* **Análisis de Distractores:**
  * A: Asume erróneamente que $\sqrt{5} < 2$.
  * C y D: Invierten el orden de los radicales.
</details>

<details>
<summary><b>Pregunta 2 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **A**
* **Procedimiento:** Descomponemos $72$ buscando el mayor factor cuadrado perfecto: $72 = 36 \cdot 2$.
  $$\sqrt{72} = \sqrt{36 \cdot 2} = \sqrt{36} \cdot \sqrt{2} = 6\sqrt{2}$$
* **Análisis de Distractores:**
  * B: Suma raíces incorrectamente ($\sqrt{64} + \sqrt{8}$).
  * C: Descompone como $9 \cdot 8 \to 3\sqrt{8}$, pero no simplifica al máximo ($\sqrt{8} = 2\sqrt{2}$).
</details>

<details>
<summary><b>Pregunta 3 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Aplicamos la propiedad $a^{\frac{m}{n}} = \sqrt[n]{a^m}$. Para $\sqrt[3]{5^2}$, el exponente del radicando es $m = 2$ y el índice es $n = 3$. Por lo tanto, equivale a $5^{2/3}$.
* **Análisis de Distractores:**
  * A: Invierte el orden de la fracción ($3/2$).
  * C: Divide $1/6$ sin relación con las propiedades de la potencia.
</details>

<details>
<summary><b>Pregunta 4 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Por definición, $\log_2(16) = x \iff 2^x = 16$. Como $2^4 = 16$, entonces $x = 4$.
* **Análisis de Distractores:**
  * A y D: Confunden el logaritmo con la división $16/8$ o $16/2$.
</details>

<details>
<summary><b>Pregunta 5 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** $\log_9\left(\frac{1}{3}\right) = x \iff 9^x = \frac{1}{3}$. Igualamos a base $3$:
  $$(3^2)^x = 3^{-1} \implies 3^{2x} = 3^{-1} \implies 2x = -1 \implies x = -\frac{1}{2}$$
* **Análisis de Distractores:**
  * A: Eleva al cuadrado con signo negativo sin considerar la base $9$.
  * D: Olvida el signo negativo de la fracción $1/3$.
</details>

<details>
<summary><b>Pregunta 6 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** En la forma canónica $f(x) = a(x-h)^2 + k$, el vértice es $(h, k)$. Para $f(x) = (x-2)^2 - 3$, el valor dentro del paréntesis cambia de signo ($h = 2$) y el término constante lo conserva ($k = -3$). Vértice: $(2, -3)$.
* **Análisis de Distractores:**
  * A: Mantiene el signo negativo del $-2$.
  * C y D: Invierten erróneamente los signos de las coordenadas.
</details>

<details>
<summary><b>Pregunta 7 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** El eje de simetría de una parábola en forma canónica es la recta vertical $x = h$. Como $f(x) = (x+1)^2 - 4$, reescribimos como $(x - (-1))^2 - 4$, luego $h = -1$. El eje es $x = -1$.
* **Análisis de Distractores:**
  * A: Confunde la recta con el valor $k = -4$.
  * C: Olvida el cambio de signo del factor $(x+1)$.
</details>

<details>
<summary><b>Pregunta 8 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Las dimensiones interiores son $(20 - 2x)$ y $(12 - 2x)$ al descontar el borde $x$ por ambos lados.
  $$\text{Área} = (20 - 2x)(12 - 2x) = 240 - 40x - 24x + 4x^2 = 240 - 64x + 4x^2$$
* **Análisis de Distractores:**
  * A: Descuenta el borde $x$ solo una vez por dimensión ($(20-x)(12-x)$).
  * C y D: Errores en la multiplicación de signos del término cuadrático.
</details>

<details>
<summary><b>Pregunta 9 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **A**
* **Procedimiento:** Despejamos el término cuadrático: $5x^2 = 45 \implies x^2 = 9 \implies x = \pm \sqrt{9} = \pm 3$. Las soluciones son $3$ y $-3$.
* **Análisis de Distractores:**
  * B: No divide por $5$ antes de extraer la raíz.
  * D: Omite la solución negativa de la ecuación cuadrática.
</details>

<details>
<summary><b>Pregunta 10 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:**
  1. $y = \sqrt{5x}$
  2. Intercambiar: $x = \sqrt{5y}$
  3. Elevar al cuadrado: $x^2 = 5y \implies y = \frac{x^2}{5}$. Luego, $h^{-1}(x) = \frac{x^2}{5}$.
* **Análisis de Distractores:**
  * A: Multiplica por $5$ en lugar de dividir.
  * C: No despeja el exponente al invertir la raíz.
</details>

<details>
<summary><b>Pregunta 11 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Por definición de función inversa, $f^{-1}(a) = b \iff f(b) = a$. Dado que $f^{-1}(4) = 10$, se cumple que $f(10) = 4$.
* **Análisis de Distractores:**
  * A: Supone erróneamente que $f(4) = 10$.
  * C y D: Alteran la relación entre dominio y recorrido.
</details>

<details>
<summary><b>Pregunta 12 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Una disminución del $20\%$ implica multiplicar por un factor de $(1 - 0,20) = 0,8$ en cada periodo. La función decreciente acumulada es $100 \cdot (0,8)^t$.
* **Análisis de Distractores:**
  * A: Utiliza un factor de aumento del $20\%$ ($1,2$).
  * C: Confunde el modelo exponencial con un modelo lineal no porcentual.
</details>

<details>
<summary><b>Pregunta 13 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Fórmula del volumen de la esfera: $V = \frac{4}{3}\pi r^3$.
  $$V = \frac{4}{3}\pi (3)^3 = \frac{4}{3}\pi (27) = 4 \cdot 9 \pi = 36\pi\text{ cm}^3$$
* **Análisis de Distractores:**
  * A: Aplica erróneamente la fórmula del área ($4\pi r^2 = 36\pi$, en unidades cuadradas y no cúbicas).
  * B: Eleva $3^2$ en lugar de $3^3$.
</details>

<details>
<summary><b>Pregunta 14 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** $\tan(\alpha) = \frac{\text{Cateto Opuesto (CO)}}{\text{Cateto Adyacente (CA)}}$.
  $$\frac{3}{4} = \frac{\text{CO}}{8} \implies \text{CO} = \frac{3 \cdot 8}{4} = 6\text{ cm}$$
* **Análisis de Distractores:**
  * A: Realiza la división $8/2$.
  * D: Calcula el valor de la hipotenusa ($10\text{ cm}$) en lugar del cateto opuesto.
</details>

<details>
<summary><b>Pregunta 15 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **A**
* **Procedimiento:** La razón seno se define como $\operatorname{sen}(\alpha) = \frac{\text{Cateto Opuesto}}{\text{Hipotenusa}} = \frac{5}{13}$.
* **Análisis de Distractores:**
  * B: Corresponde al coseno ($\cos(\alpha) = 12/13$).
  * C: Corresponde a la tangente ($\tan(\alpha) = 5/12$).
</details>

<details>
<summary><b>Pregunta 16 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** La representación vectorial es $(u \cos \theta, u \operatorname{sen} \theta)$. La proyección vectorial **sobre el eje Y** anula la componente $X$ ($0$) y mantiene la vertical: $(0, 10 \operatorname{sen} 30^\circ)$.
* **Análisis de Distractores:**
  * A: Corresponde a la proyección sobre el eje $X$.
  * C: Utiliza la función coseno para el eje vertical.
</details>

<details>
<summary><b>Pregunta 17 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Una variable aleatoria asigna un valor numérico real al resultado de un experimento aleatorio. En este caso, la cantidad de fichas rojas depende del azar.
* **Análisis de Distractores:**
  * A y C: Son parámetros fijos del experimento, no variables numéricas aleatorias.
</details>

<details>
<summary><b>Pregunta 18 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** El espacio muestral tiene $N = 4$ casos equiprobables $\{1, 2, 3, 4\}$. El evento $X=2$ representa $1$ caso favorable:
  $$P(X=2) = \frac{1}{4}$$
* **Análisis de Distractores:**
  * D: Corresponde a la probabilidad complementaria $P(X \neq 2) = 3/4$.
</details>

<details>
<summary><b>Pregunta 19 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Selección de un grupo donde el orden NO importa $\implies$ Combinación $C(7, 3)$:
  $$C(7, 3) = \frac{7!}{3!(7-3)!} = \frac{7 \cdot 6 \cdot 5}{3 \cdot 2 \cdot 1} = 35$$
* **Análisis de Distractores:**
  * A: Multiplica directamente $7 \cdot 3 = 21$.
  * D: Aplica variaciones dividiendo mal por $5$.
</details>

<details>
<summary><b>Pregunta 20 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **A**
* **Procedimiento:**
  * Total de ordenamientos: $P_4 = 4! = 24$.
  * Casos favorables: $2$ formas de ubicar los libros en los extremos $\times 2!$ formas de ordenar los $2$ libros del centro $= 4$ casos.
  * Probabilidad $= \frac{4}{24} = \frac{1}{6}$.
* **Análisis de Distractores:**
  * B y C: Mal conteo de las permutaciones internas.
</details>

<details>
<summary><b>Pregunta 21 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Multiplicación de radicales del mismo índice:
  $$\sqrt{12} \cdot \sqrt{3} = \sqrt{12 \cdot 3} = \sqrt{36} = 6$$
* **Análisis de Distractores:**
  * C: Conserva una raíz innecesaria ($6\sqrt{3}$).
  * D: Multiplica directo sin extraer la raíz cuadrada.
</details>

<details>
<summary><b>Pregunta 22 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:**
  1. $\log_2(\sqrt{8}) = \log_2(8^{1/2}) = \log_2((2^3)^{1/2}) = \log_2(2^{3/2}) = \frac{3}{2}$
  2. $\log_2(4) = 2$
  3. Suma: $\frac{3}{2} + 2 = \frac{7}{2}$
* **Análisis de Distractores:**
  * A: Suma $3/2 + 1$.
  * D: Asume erróneamente que $\log_2(\sqrt{8}) = 2$.
</details>

<details>
<summary><b>Pregunta 23 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Simplificamos los términos semejantes:
  * $\sqrt{75} = \sqrt{25 \cdot 3} = 5\sqrt{3}$
  * $\sqrt{12} = \sqrt{4 \cdot 3} = 2\sqrt{3}$
  Resta: $5\sqrt{3} - 2\sqrt{3} = 3\sqrt{3}$.
* **Análisis de Distractores:**
  * A: Resta las cantidades subradicales dentro de la raíz ($\sqrt{75-12} = \sqrt{63}$, erróneo).
</details>

<details>
<summary><b>Pregunta 24 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Sustituimos $c = 2 \cdot 10^{-4}$ en $\text{pH} = -\log(c)$:
  $$\text{pH} = -\log(2 \cdot 10^{-4}) = -[\log 2 + \log 10^{-4}] = -[\log 2 - 4] = 4 - \log 2$$
* **Análisis de Distractores:**
  * A: Error al distribuir el signo negativo.
  * C: Mantiene ambos términos negativos.
</details>

<details>
<summary><b>Pregunta 25 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Para $f(x) = a(x-h)^2 + k$, el eje de simetría es la recta vertical $x = h$. En $f(x) = (x-3)^2 + 2$, identificamos $h = 3$, por lo que la recta es $x = 3$.
* **Análisis de Distractores:**
  * A: Invierte el signo del parámetro $h$.
  * B y D: Confunden la coordenada $x$ con $k = 2$.
</details>

<details>
<summary><b>Pregunta 26 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **A**
* **Procedimiento:** Probamos la alternativa A con los puntos dados:
  * $f(0) = 0^2 - 2(0) - 3 = -3$
  * $f(1) = 1^2 - 2(1) - 3 = -4$
  * $f(3) = 3^2 - 2(3) - 3 = 0$
  Todas las condiciones se cumplen únicamente para $x^2 - 2x - 3$.
* **Análisis de Distractores:**
  * B: Entrega $f(1) = 0$.
  * C: Entrega $f(1) = -6$.
</details>

<details>
<summary><b>Pregunta 27 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** La intersección con el eje $Y$ ocurre en $x = 0$:
  $$f(0) = 2(0)^2 - 3(0) + 5 = 5 \implies (0, 5)$$
* **Análisis de Distractores:**
  * D: Invierte el orden de las coordenadas en el plano cartesiano ($(5, 0)$).
</details>

<details>
<summary><b>Pregunta 28 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:** Factorizamos $x^2 - 5x + 6 = 0 \implies (x-2)(x-3) = 0$. Las soluciones son $x = 2$ y $x = 3$. Por lo tanto, $2$ es una solución válida.
* **Análisis de Distractores:**
  * A, C y D: No satisfacen la igualdad al reemplazar $x$ en la ecuación.
</details>

<details>
<summary><b>Pregunta 29 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Resolver $g^{-1}(15) = x$ equivale a encontrar $x$ tal que $g(x) = 15$:
  $$5x - 10 = 15 \implies 5x = 25 \implies x = 5$$
* **Análisis de Distractores:**
  * A: Resta $10$ en lugar de sumarlo al despejar.
  * B: Divide $15/5$ ignorando el término constante.
</details>

<details>
<summary><b>Pregunta 30 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **A**
* **Procedimiento:** El incremento neto entre dos periodos consecutivos corresponde al $6\%$ del valor actual: $f(t+1) - f(t) = 0,06 \cdot f(t)$.
* **Análisis de Distractores:**
  * C: Corresponde al valor total acumulado $f(t+1) = 1,06 \cdot f(t)$, no al incremento solo.
</details>

<details>
<summary><b>Pregunta 31 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Producción con incremento del $10\%$ mensual (factor $1,1$):
  * Mes 1: $1.500$
  * Mes 2: $1.500 \cdot 1,1 = 1.650$
  * Mes 3: $1.650 \cdot 1,1 = 1.815$
* **Análisis de Distractores:**
  * A: Es la producción del segundo mes.
  * B: Asume un modelo lineal ($+150$ cada mes).
</details>

<details>
<summary><b>Pregunta 32 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Área superficial de la esfera: $A = 4\pi r^2$. Con $r = 5\text{ cm}$:
  $$A = 4 \cdot \pi \cdot 5^2 = 4 \cdot 25 \cdot \pi = 100\pi\text{ cm}^2$$
* **Análisis de Distractores:**
  * A: Olvida multiplicar por el coeficiente $4$.
  * D: Confunde el exponente del radio con la fórmula del volumen.
</details>

<details>
<summary><b>Pregunta 33 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **B**
* **Procedimiento:**
  1. Volumen de una esfera de $r = 1\text{ cm}$ con $\pi \approx 3$:
     $$V_{\text{esfera}} = \frac{4}{3} \cdot 3 \cdot 1^3 = 4\text{ cm}^3$$
  2. Número de esferas completas en $20\text{ cm}^3$:
     $$\text{Cantidad} = \frac{20}{4} = 5 \text{ esferas}$$
* **Análisis de Distractores:**
  * A y C: Errores al no simplificar el valor aproximado de $\pi \approx 3$.
</details>

<details>
<summary><b>Pregunta 34 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **A**
* **Procedimiento:** $\cos(\alpha) = \frac{\text{Cateto Adyacente}}{\text{Hipotenusa}} = \frac{9}{15}$. Simplificando por $3$: $\frac{3}{5}$.
* **Análisis de Distractores:**
  * B: Corresponde al valor de $\operatorname{sen}(\alpha) = 12/15 = 4/5$.
</details>

<details>
<summary><b>Pregunta 35 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** $\tan(\alpha) = \frac{\text{Ascenso}}{\text{Avance}} \implies 0,6 = \frac{\text{Ascenso}}{2.400}$.
  $$\text{Ascenso} = 0,6 \cdot 2.400 = 1.440\text{ m}$$
* **Análisis de Distractores:**
  * D: Realiza la división $2.400 / 0,6 = 4.000$ en lugar de multiplicar.
</details>

<details>
<summary><b>Pregunta 36 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** La palabra SOL contiene 2 consonantes (S, L) y 1 vocal (O). Al extraer 2 letras sin reposición, las consonantes obtenidas pueden ser 0 (si sale O con otra letra en caso extendido), 1 (O y una consonante) o 2 (S y L). El recorrido completo de la variable aleatoria discreta $X$ es $\{0, 1, 2\}$.
* **Análisis de Distractores:**
  * D: Incluye el valor $3$, el cual es imposible ya que solo se extraen $2$ letras.
</details>

<details>
<summary><b>Pregunta 37 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** El evento $X \ge 2$ suma las probabilidades de $X = 2$ y $X = 3$:
  $$P(X \ge 2) = P(X=2) + P(X=3) = \frac{1}{3} + \frac{1}{6} = \frac{2}{6} + \frac{1}{6} = \frac{3}{6} = \frac{1}{2}$$
* **Análisis de Distractores:**
  * A y B: Seleccionan una sola probabilidad de la suma.
</details>

<details>
<summary><b>Pregunta 38 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:** Ordenar 4 tarjetas distintas sin repetición es una Permutación $P_4$:
  $$P_4 = 4! = 4 \cdot 3 \cdot 2 \cdot 1 = 24 \text{ números}$$
* **Análisis de Distractores:**
  * D: Permite repetición de dígitos ($4^4 = 256$).
</details>

<details>
<summary><b>Pregunta 39 — Ver solución y retroalimentación</b></summary>
<br>

* **Respuesta Correcta:** **C**
* **Procedimiento:**
  * Casos totales: $C(5, 2) = \frac{5 \cdot 4}{2} = 10$.
  * Caso contrario (ningún interesado seleccionado $\implies$ elegir 2 de los 2 no interesados): $C(2, 2) = 1$.
  * Probabilidad del complemento $= \frac{1}{10}$.
  * Probabilidad pedida $= 1 - \frac{1}{10} = \frac{9}{10}$.
* **Análisis de Distractores:**
  * A: Equivoca la probabilidad del evento buscando el complemento.
</details>