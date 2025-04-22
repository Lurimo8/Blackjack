# 🃏 Blackjack - Juego de Cartas en TypeScript (CLI)

Este proyecto es una implementación simplificada del clásico juego de Blackjack, desarrollada con **TypeScript** y ejecutada desde la línea de comandos usando **Node.js**. El objetivo es acercarse lo más posible a 21 sin pasarse, 
enfrentando al dealer con acciones básicas de **"Hit"** o **"Stand"**.

---

## 📌 Características

- Juego en consola completamente funcional.
- Apuestas gestionadas con un bankroll inicial de $100.
- Reparto automático de cartas con lógica realista.
- Cálculo automático de Blackjack, Busted, Push y Ganadores.
- Soporte para valor dual del As (1 u 11).
- Dealer automático con reglas estándar (se planta en 17 o más).
- Lógica de pago 3:2 para Blackjack natural.
- Gestión de múltiples rondas hasta que el jugador se quede sin fondos.

---

## 🛠 Tecnologías utilizadas

- **TypeScript** – Tipado fuerte y OOP.
- **Node.js** – Entorno de ejecución.
- **prompt-sync** – Entrada del usuario desde consola.

---

## ▶️ Cómo ejecutar el juego

1. Instala dependencias:
npm install prompt-sync
npm i --save-dev @types/prompt-sync

2. Compila el proyecto:
   tsc

3. Ejecuta el juego desde el archivo compilado
   node app.js

