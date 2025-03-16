# Bot de Trading con Backtrader

## ✨ Descripción
Este es un **bot de trading** básico basado en la librería **Backtrader**, diseñado para operar con **Bitcoin (BTC)** usando el indicador **RSI (Relative Strength Index)**. Este bot simula la compra y venta de BTC según las señales generadas por el RSI.

---

## 👨‍💻 ¿Qué es un Bot de Trading?
Un **bot de trading** es un programa que ejecuta operaciones automáticas en los mercados financieros según una estrategia predefinida. Los bots pueden analizar datos históricos, identificar patrones y tomar decisiones de compra/venta sin intervención humana.

---

## 🔄 ¿Qué es Backtrader?
**Backtrader** es una plataforma de **backtesting** en Python utilizada para evaluar estrategias de trading sobre datos históricos. Permite simular operaciones, calcular indicadores técnicos y analizar resultados de manera eficiente.

**Ventajas de Backtrader:**
- Soporta varios tipos de datos (CSV, API, bases de datos).
- Compatible con múltiples indicadores técnicos (RSI, MACD, medias móviles, etc.).
- Permite crear estrategias personalizadas con flexibilidad.
- Genera visualizaciones y reportes automáticos.

---

## 🌐 Instalación
Antes de ejecutar el bot, instala las dependencias necesarias:

```bash
pip install backtrader pandas matplotlib
```

---

## ⚙️ Uso
1. **Cargar datos históricos:** El bot utiliza un archivo CSV llamado `btc_data.csv` con datos de Bitcoin.
2. **Ejecutar el bot:**
   ```bash
   python bot_rsi.py
   ```
3. **Ver resultados:** Se mostrará el saldo final y un gráfico con las operaciones realizadas.

---

## 🔢 Estrategia Utilizada
Este bot emplea el indicador **RSI (Relative Strength Index)** para determinar puntos de entrada y salida:

- **Compra BTC** cuando el RSI cae por debajo de **30** (zona de sobreventa).
- **Vende BTC** cuando el RSI supera **70** (zona de sobrecompra).

---

## 📝 Posibles Mejoras
A continuación, algunas mejoras para optimizar la estrategia:

- ✅ **Optimización de parámetros:** Ajustar el periodo del RSI (ej. 10, 20, 30 días).
- ✅ **Agregar Stop-Loss y Take-Profit:** Para reducir riesgos y asegurar ganancias.
- ✅ **Usar otros indicadores:** Combinar RSI con medias móviles o MACD para señales más precisas.
- ✅ **Conexión en tiempo real:** Integrar APIs de Binance o Bybit para operar en mercados reales.

---

## 🎨 Visualización
El bot genera un **gráfico** con:
- Precio de BTC.
- RSI.
- Señales de compra y venta.

---

## 👥 Contribución
Si quieres mejorar el bot, síguelo y haz un pull request en este repositorio.

---

## 📈 Contacto
Si tienes dudas o sugerencias, puedes contactarme en [tu correo o redes sociales].

---

## 🛠️ Licencia
Este proyecto está bajo la licencia MIT.

