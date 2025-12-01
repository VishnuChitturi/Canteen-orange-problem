#  3D Canteen Visualization & Real-time Interaction – Blender + Three.js

##  Project Structure
Canteen-orange-problem/
│
├── index.html     # Entry point of the web application
├── app.js         # Main JavaScript file containing logic & controls
├── styles.css     # Styling file for UI elements
└── model.glb      # 3D model used in the simulation

---

##  How to Run the Project
```
You must use a local HTTP server, otherwise the 3D model will not load due to browser security restrictions.

Step 1: Open Terminal inside the project folder
cd Canteen-orange-problem

Step 2: Start the local server
python -m http.server 8000

Step 3: Open the project in browser
http://localhost:8000
```

##  Controls
```
Key / Action	Description
W / A / S / D	Move forward / left / backward / right
Arrow Keys	Look around (rotate camera)
Mouse	Look around (First-person mode)
V	Toggle view (First-person / Third-person)
Shift	Sprint (move faster)
Space	Move upwards
C	Move downwards
```

##  Technical Details
```
Built using:
Three.js → For 3D rendering
JavaScript (app.js) → Main logic and camera movement
GLTFLoader → To load model.glb
CSS (styles.css) → For UI enhancements
HTML (index.html) → Root application file
```

## Browser Requirements
```
WebGL must be enabled
Use a modern browser (Chrome, Firefox, Edge recommended)
Do not directly open index.html via file explorer (file://) – use http://localhost:8000
