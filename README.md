# Hydrangea Water Automata 🌸🐟

![Hero](assets/Evision_260529.png)

A living generative artwork: endless hydrangea fields under glass-like water, sunlight reflections, and koi fish swimming gracefully.

## Concept

This project treats the canvas as a living field. Each cell stores color, water, bloom energy, and hidden neural states. Local neural rules create hydrangea-like structures, ripples, mist, and liquid light.

## Steps / Stages

1. **Procedural Water Field** – Generate initial 2D color & water grid.
2. **Hydrangea CA** – Basic cellular automata grow flower clusters.
3. **Neural CA Training** – Neural network learns to reproduce target hydrangea images.
4. **Cinematic Rendering** – Apply glass-water, sunlight, petals, and mist.
5. **Koi Layer** – Animated fish swim over the water.
6. **Interactive Recording** – Capture GIF/MP4 sessions of the living canvas.
7. **Artistic Polishing** – Adjust color, caustics, and lighting for art-like feel.

## Gallery

*Neural CA growth animation.* (to be released soon...)

*Koi swimming layer.* (to be released soon...)

*Final artistic vision.* (to be released soon...)

## Run Locally

```bash
git clone https://github.com/ChenCheng-976/hydrangea-water-automata.git
cd YOUR_REPO
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python stage10_koi_fish_layer.py
