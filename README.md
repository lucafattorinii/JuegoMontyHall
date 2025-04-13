# 🎲 Juego Monty Hall - Simulación en Java

Este proyecto simula el famoso problema de Monty Hall utilizando Java. Permite entender cómo cambia la probabilidad de ganar al cambiar o no de puerta luego de que el presentador revela una opción vacía.

---

## 📌 ¿Qué es el problema de Monty Hall?

Es un juego de tres puertas:  
- Detrás de una hay un **premio**, detrás de las otras dos **no hay nada**.  
- El jugador elige una puerta.  
- Luego, el anfitrión revela una puerta vacía entre las otras dos.  
- El jugador debe decidir si **mantener su elección inicial** o **cambiar a la otra puerta restante**.  

La paradoja: **Cambiar de puerta aumenta las chances de ganar de 1/3 a 2/3**.

---

## 🧠 ¿Qué incluye este proyecto?

- 📦 Lógica del juego: Clases `JuegoMontyHall` y `Puerta`
- 🔁 Simulador que ejecuta 1000 juegos para comparar las probabilidades
- 📈 Resultados estadísticos impresos por consola
- 🧪 Test en consola (sin JUnit) desde clase `SimuladorMontyHall`

---

## 🛠️ Cómo correr el proyecto

1. Cloná el repositorio o descargalo como ZIP:
   ```bash
   git clone https://github.com/lucafattorinii/JuegoMontyHall.git
