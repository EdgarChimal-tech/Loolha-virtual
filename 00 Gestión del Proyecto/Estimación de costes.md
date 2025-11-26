# Estimación de Costes y Esfuerzo

## IFPUG – UFP  
**(Unadjusted Function Points — Puntos de función no ajustado)**

Nuestro equipo de desarrollo es de 4 personas, con una productividad de **20 puntos de función por mes** y un costo promedio de **10,000 pesos mensuales**.

- Costo por punto de función:  
  **10000 / 20 = 500 pesos**

- Costo total del proyecto:  
  **76 × 500 = 38,000 pesos**

- Esfuerzo total:  
  **76 / 20 = 3.8 persona-mes**

---

## COCOMO  
**(Constructive Cost Model — Modelo Constructivo de Costos)**

El proyecto es de tipo **orgánico y básico**.  
Parámetros según la guía:

- a = 2.4  
- b = 1.05  
- c = 2.5  
- d = 0.38  
- KLOC ≈ 1.5

Cálculos:

- **Esfuerzo:**  
  *E = a × KLOCᵇ*  
  E = 2.4 × 1.5¹·⁰⁵ = **3.672 persona-mes**

- **Tiempo:**  
  *T = c × Eᵈ*  
  T = 2.5 × 3.672⁰·³⁸ = **4.1 meses**

- **Personal requerido:**  
  *P = E / T*  
  P = 3.672 / 4.1 = **0.9 personas**