# McPath

A browser-based 3D racing prototype built with **Three.js**, inspired by real-world Formula 1 circuits such as Silverstone.

---

## Features

* Custom-built race tracks based on real F1 layouts
* Player-controlled vehicle (keyboard input)
* Dynamic third-person and free-flight camera modes
* Fully rendered 3D environment using WebGL
* Lightweight — runs directly in the browser (no install required)

---

## Controls

### Driving

| Key      | Action          |
| -------- | --------------- |
| ⬆️ Arrow | Accelerate      |
| ⬇️ Arrow | Brake / Reverse |
| ⬅️ Arrow | Turn Left       |
| ➡️ Arrow | Turn Right      |

---

### Setup (Plug & Play)

Some browsers restrict features (like pointer lock), so run a local server:

#### Using Python:

```bash
python -m http.server
```

#### Using Node.js:

```bash
npx serve
```

Then open:

```
http://localhost:8000
```

---

## Built With

* Three.js — 3D rendering engine (WebGL)
* JavaScript (ES6)
* HTML5

---

## Roadmap

Planned improvements:

* Realistic car physics (acceleration, grip, drifting)
* Track limits & collision detection
* Kerbs and track detailing
* Lap timing system
* Multiple real-world tracks

---

## Inspiration

This project is inspired by real Formula 1 circuits, especially:

* Silverstone Circuit

---

## Notes

* This is an early prototype — physics and visuals are still being improved
* Track layouts are approximations, not exact replicas

---

## Contributing

Feel free to fork the project and experiment:

* Add new tracks
* Improve physics
* Enhance visuals

Pull requests are welcome

---

## License

This project is open-source and available under the MIT License.

---

## 💡 Author

Built as a learning project exploring:

* 3D game development in the browser
* Real-time rendering
* Racing game mechanics

---

Enjoy driving 🏁
