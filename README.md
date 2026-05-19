# 📊 Más allá de las medias: Introducción al ANOVA

Este repositorio contiene el material de la **Píldora Formativa sobre ANOVA (Análisis de Varianza)**. Una guía diseñada para analistas de datos que necesitan comparar múltiples grupos de forma rigurosa y eficiente.

---

## 🎯 Objetivo de la Presentación
El objetivo es entender por qué no podemos usar múltiples pruebas *t-Student* para comparar 3 o más grupos y cómo el **Estadístico F** nos permite tomar decisiones basadas en datos sin aumentar el riesgo de falsos positivos (Error Tipo I).

---

## 🗺️ Estructura de la Píldora (20 min)

La presentación se divide en 9 bloques estratégicos:

1.  **Portada** 🎨: Introducción al reto de comparar múltiples grupos.
2.  **El Problema** ⚠️: El peligro del error acumulado (Por qué 3 *t-tests* son una mala idea).
3.  **La Solución** 💡: Definición de ANOVA y la paradoja de comparar medias analizando varianzas.
4.  **La Intuición** 🔍: Diferenciando la variabilidad *Entre* grupos vs. *Dentro* de los grupos (Ruido).
5.  **El Estadístico F** ⚙️: La fórmula del motor de ANOVA:
    $$F = \frac{\text{Variabilidad ENTRE}}{\text{Variabilidad DENTRO}}$$
6.  **Hipótesis** ⚖️: Definición de $H_0$ (Igualdad) y $H_1$ (Diferencia), y el criterio del $p\text{-valor} < 0.05$.
7.  **Post-Hoc** 🕵️: ¿Qué pasa cuando ANOVA dice "sí"? Uso de la prueba de **Tukey** para encontrar al "culpable".
8.  **Casos de Uso Real** 🚀: Aplicaciones en E-commerce, UX y Recursos Humanos.
9.  **Conclusiones** ✅: Resumen ejecutivo para el analista.

---

## 🛠️ Conceptos Clave Dominados
*   **Error Tipo I**: Evitar falsos positivos por azar.
*   **Variabilidad (Between vs Within)**: Entender qué parte del dato es señal y qué parte es ruido.
*   **Pruebas Post-Hoc**: Análisis de comparaciones múltiples tras resultados significativos.

---

## 💼 ¿Dónde se aplica?
| Sector | Aplicación |
| :--- | :--- |
| **E-commerce** | Ticket medio según método de pago (Bizum vs PayPal vs Tarjeta). |
| **Producto/UX** | Tiempo de permanencia según 4 diseños de interfaz (Test A/B/C/D). |
| **RRHH** | Productividad según modelo de trabajo (Remoto vs Híbrido vs Presencial). |

---

