# Rock Paper Scissors Life Simulation

A simple life-like simulation based on **Rock–Paper–Scissors** rules, built with **Python** and **Pygame**.

Entities of three types — **Rock**, **Paper**, and **Scissors** — move freely in a 2D space.
When two entities collide, the loser transforms into the winner, following classic rules:

* Rock loses to Paper → Rock becomes Paper
* Paper loses to Scissors → Paper becomes Scissors
* Scissors loses to Rock → Scissors becomes Rock

Over time, populations evolve dynamically until one type dominates the simulation.

---

## Features

* Real-time autonomous movement
* Rock–Paper–Scissors interaction logic
* Visual representation using textures
* Simple emergent behavior simulation
* Minimalistic and lightweight implementation

---

## Requirements

* Python **3.8+**
* **pygame**

Install dependencies:

```bash
pip install pygame
```

---

## Running the Project

1. Clone the repository
2. Make sure the following image files are present in the project root:

   * `paper.png`
   * `stone.png`
   * `scissors.png`
3. Run the simulation:

```bash
python main.py
```

---

## How It Works

* Each entity moves randomly within window bounds
* Collision detection uses rectangular hitboxes
* On collision, the losing entity changes its type and joins the winner’s group
* The simulation continuously updates and renders the state

---

## Author

Created by [abik](https://github.com/abi4ka)
