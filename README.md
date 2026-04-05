# 🌊 Density & Buoyancy Explorer

An interactive, browser-based tool for students to explore how mass and volume relate to density and buoyancy.

## What It Does

Drag objects into a water tank to see whether they float or sink — and understand **why** based on their density.

## Features

- **10 preset objects** with real-world densities: cork, wood, ice, plastic, rubber, bone, aluminum, granite, steel, and gold
- **Drag & drop** objects into the water tank
- **Accurate float/sink physics** — floating objects show the correct percentage submerged based on Archimedes' principle
- **Object Inspector** — displays mass, volume, density calculation, and % submerged for each object
- **Live formula panel** — shows `ρ = m ÷ V` filled in with real values
- **Custom object creator** — students enter any mass and volume to test their own hypotheses
- **Toggle labels** and **delete objects** to keep the tank organized
- No installation or internet required — runs entirely in the browser

## How to Use

1. Open `index.html` in any modern web browser
2. Drag an object from the left panel into the water tank
3. Watch it float or sink, then check the Object Inspector panel on the right
4. Try the **Custom Object** form to test your own mass and volume combinations
5. Press **Delete** to remove a selected object, or **Clear Tank** to reset

## The Science

> **Density = Mass ÷ Volume** (unit: g/cm³)

An object floats in water if its density is **less than 1.0 g/cm³** (the density of water). If it's greater, it sinks.

When floating, the fraction of the object submerged equals the ratio of its density to the fluid's density — this is **Archimedes' Principle**.

| Object   | Density (g/cm³) | Behavior |
|----------|----------------|----------|
| Cork     | 0.24           | Floats   |
| Ice      | 0.917          | Floats   |
| Plastic  | 0.95           | Floats   |
| Water    | 1.000          | —        |
| Aluminum | 2.70           | Sinks    |
| Steel    | 7.85           | Sinks    |
| Gold     | 19.32          | Sinks    |

## Live Demo

Enable GitHub Pages (Settings → Pages → Deploy from `main`) to share a live link with students.
