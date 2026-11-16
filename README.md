# 🌌 Black Hole Simulator

<p align="center">
  <img src="https://assets.science.nasa.gov/dynamicimage/assets/science/psd/solar/2023/09/h/hires.jpg?crop=faces%2Cfocalpoint&fit=clip&h=2330&w=4000" width="850" alt="The first image of the supermassive black hole M87*">
</p>

<h3 align="center">Exploring the Universe Beyond the Event Horizon</h3>

<p align="center">
  An interactive black hole simulation combining computational physics, real-time visualization, and astronomical science.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-Physics_Engine-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/React-Interface-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Three.js-3D_Rendering-black?style=flat-square&logo=threedotjs" alt="Three.js">
  <img src="https://img.shields.io/badge/FastAPI-Backend-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
</p>

---

## 🪐 About

**Black Hole Simulator** is a scientific visualization project dedicated to exploring black holes and the extreme physical phenomena surrounding them.

The project brings together mathematical models, computational algorithms, and interactive 3D graphics to illustrate how gravity affects light, matter, and spacetime.

Users can explore black hole parameters, observe gravitational lensing, investigate particle trajectories, and visualize the structures surrounding these extraordinary cosmic objects.

The project focuses on the intersection of **physics, astronomy, computer graphics, and software engineering**.

## 🌑 What Is a Black Hole?

A black hole is a region of spacetime where gravity is so strong that nothing can escape from within its event horizon, not even light.

Black holes can form through the gravitational collapse of massive stars. Much larger black holes, containing millions or billions of solar masses, reside in the centers of many galaxies.

Despite their name, black holes are not simply cosmic vacuum cleaners. At sufficiently large distances, their gravitational influence behaves like that of any other object with the same mass.

### The Event Horizon

The event horizon is the boundary beyond which escaping to the outside Universe is impossible.

For a non-rotating, uncharged black hole, its radius is given by the Schwarzschild radius:

$$
r_s = \frac{2GM}{c^2}
$$

Where:

* \(r_s\) — Schwarzschild radius.
* \(G\) — gravitational constant.
* \(M\) — black hole mass.
* \(c\) — speed of light in vacuum.

The Schwarzschild radius increases linearly with mass. A black hole ten times more massive has ten times the Schwarzschild radius.

### Gravitational Lensing

Gravity affects the paths of light. Near a black hole, light can follow strongly curved trajectories, producing distorted, magnified, or multiple images of objects behind it.

This phenomenon is known as **gravitational lensing**.

It is responsible for many of the remarkable visual structures associated with black holes, including the bright rings surrounding their apparent shadows.

### Accretion Disks

Gas and dust falling toward a black hole can form a rotating structure known as an accretion disk.

Friction and other processes heat the material, causing it to emit radiation. The resulting light can make the surroundings of a black hole extremely bright, even though the black hole itself emits no light from within its event horizon.

### Rotating Black Holes

A rotating black hole is described by the Kerr solution of general relativity.

Its rotation affects the surrounding spacetime through a phenomenon called **frame dragging**. This changes the behavior of matter and light near the black hole and makes its geometry more complicated than that of a non-rotating black hole.

---

## 🔭 Famous Black Holes

### TON 618 — A Giant of the Observable Universe

<p align="center">
  <img src="https://svs.gsfc.nasa.gov/vis/a010000/a014300/a014335/SMBH_Scale_Still_1.jpg" width="850" alt="NASA visualization comparing supermassive black holes, including TON 618">
</p>

*Artist's visualization: NASA's comparison of supermassive black holes by the sizes of their shadows.*

TON 618 is an extremely distant quasar associated with one of the most massive known black holes.

NASA describes TON 618 as containing more than 60 billion solar masses. Its enormous scale illustrates just how extreme supermassive black holes can become.

Because TON 618 is observed as a quasar, much of what astronomers learn about it comes from radiation emitted by its surrounding environment rather than from a direct image of the black hole.

### M87* — The First Black Hole Image

<p align="center">
  <img src="https://assets.science.nasa.gov/dynamicimage/assets/science/psd/solar/2023/09/h/hires.jpg?crop=faces%2Cfocalpoint&fit=clip&h=2330&w=4000" width="700" alt="The shadow of the supermassive black hole M87*">
</p>

M87* is the supermassive black hole at the center of the galaxy Messier 87.

In April 2019, the Event Horizon Telescope collaboration released the first image of a black hole's shadow. The image revealed a bright ring of emission surrounding a darker central region.

* **Location:** Galaxy Messier 87.
* **Mass:** Approximately 6.5 billion solar masses.
* **Significance:** First released image of a black hole's shadow.

### Sagittarius A* — Our Galactic Center

<p align="center">
  <a href="https://www.nsf.gov/news/media-toolkits/event-horizon-telescope">
    <img src="https://nsf-gov-resources.nsf.gov/2024-12/sag-event-image.jpg" width="700" alt="The Event Horizon Telescope image of Sagittarius A*">
  </a>
</p>

*Image source: Event Horizon Telescope Collaboration, via the U.S. National Science Foundation.*

Sagittarius A* is the supermassive black hole located at the center of the Milky Way.

Despite being much less massive than M87*, it is far closer to Earth, making it an important target for studying the properties of supermassive black holes.

* **Location:** Center of the Milky Way.
* **Mass:** Approximately 4 million solar masses.
* **Significance:** The supermassive black hole at the center of our galaxy.

---

## ⚙️ Simulation Capabilities

The simulator brings physical concepts into an interactive computational environment.

| Component             | Purpose                                              |
| --------------------- | ---------------------------------------------------- |
| Black hole models     | Represent non-rotating and rotating black holes      |
| Gravitational lensing | Visualize the deflection of light                    |
| Accretion disk        | Render the hot matter surrounding a black hole       |
| Photon trajectories   | Explore light paths near strong gravitational fields |
| Particle simulation   | Investigate motion under a selected physical model   |
| 3D visualization      | Explore the scene from different camera angles       |
| Parameter controls    | Experiment with mass, spin, and viewing distance     |

The accuracy of each result depends on the physical model and numerical method used. Visual approximations are distinguished from calculations based on relativistic equations.

## 🏗️ Repository Architecture

The project is designed around separate computational, visualization, and application layers.

| Technology           | Responsibility                                                |
| -------------------- | ------------------------------------------------------------- |
| **C++**              | Physics calculations and computationally intensive simulation |
| **React**            | Interactive application interface                             |
| **TypeScript**       | Frontend logic and type safety                                |
| **Three.js / WebGL** | Real-time 3D graphics and visualization                       |
| **Python / FastAPI** | HTTP API and application services                             |
| **Docker Compose**   | Service orchestration and reproducible environments           |

This separation allows the rendering layer, computational engine, and application services to evolve independently.

## 📐 Physical Models

The project focuses on two important solutions of general relativity.

**Schwarzschild metric** — describes the spacetime outside an idealized, spherical, non-rotating, uncharged black hole.

**Kerr metric** — describes the spacetime outside an idealized, rotating, uncharged black hole.

These models provide a theoretical foundation for studying event horizons, orbital motion, and the behavior of light in strong gravitational fields.

A scientifically meaningful simulation must account for the assumptions and limitations of the selected model rather than treating every visual effect as an exact physical result.

---

## 📚 References

* [NASA — Black Holes](https://science.nasa.gov/universe/black-holes/)
* [NASA — First Image of a Black Hole](https://science.nasa.gov/resource/first-image-of-a-black-hole/)
* [NASA — Comparing the Sizes of Black Holes](https://svs.gsfc.nasa.gov/14335/)
* [U.S. National Science Foundation — Event Horizon Telescope](https://www.nsf.gov/news/media-toolkits/event-horizon-telescope)
* [Event Horizon Telescope Collaboration](https://eventhorizontelescope.org/)
* [Einstein Online — Black Holes](https://www.einstein-online.info/en/spotlight/black_holes/)

<p align="center">
  <sub>Physics · Astronomy · Computational Science · Real-Time Graphics</sub>
</p>

<p align="center">
  <strong>Explore gravity. Visualize spacetime. Discover the Universe.</strong>
</p>
