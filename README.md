# AIR Neuro

**Sistema de neurofeedback en tiempo real para música ambiental adaptativa.**

AIR transforma señales EEG en control musical en tiempo real. Detecta estados cognitivos (Reset, Focus, Flow, Deep) y modifica dinámicamente los parámetros de la música ambiental para guiar o reforzar el estado deseado.

---

## ✨ Características

- Streaming EEG en tiempo real con **BrainFlow** (Muse S, OpenBCI o Synthetic)
- Visualización en vivo con **Matplotlib** (señal cruda + potencias de banda)
- Cálculo de métricas (Alpha, Theta, Beta + ratios)
- Envío de valores normalizados por **OSC** para control de audio
- Mapeo configurable EEG → parámetros de audio (drone, brillo, evolución, recompensa)
- Diseño orientado a **estados cognitivos** más que a entrenamiento clínico

---

## 🧠 Concepto

En lugar de música estática, AIR funciona como un **sistema operativo emocional** para creadores:

- Cada estado tiene una función específica (limpiar ruido mental, sostener foco, facilitar flujo creativo, profundizar).
- La música no compite por ser “la mejor”, sino por ocupar el lugar correcto en el mapa mental.
- El neurofeedback permite que la música **responda al cerebro en tiempo real** (closed-loop).

---

## 🚀 Inicio rápido

```bash
git clone https://github.com/Zonarte/air-neuro.git
cd air-neuro
pip install -r requirements.txt
python src/air_neuro_visualizer.py
