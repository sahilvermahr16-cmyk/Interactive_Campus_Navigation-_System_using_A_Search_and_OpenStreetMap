# 🗺️ Interactive Campus Navigation System using A* Search and OpenStreetMap

An interactive web-based campus navigation system that visualizes **OpenStreetMap (OSM)** data, enables users to search locations, select source and destination points, and computes the shortest route using the **A* Search Algorithm**. Built with **HTML5 Canvas**, **JavaScript**, and **Tailwind CSS**, the project demonstrates how graph algorithms can be applied to solve real-world navigation problems.

---

## 🎥 Demo

<p align="center">
  <img src="demo.gif" alt="Project Demo" width="900">
</p>

---

## 📸 Home Page

<p align="center">
  <img src="home.png" alt="Home Page" width="900">
</p>

---

## 🌐 Live Demo

> **GitHub Pages:** https://your-username.github.io/Interactive-Campus-Navigation-System/

*(Replace `your-username` with your GitHub username after deployment.)*

---

# 📌 Project Overview

This project provides an interactive navigation system that allows users to explore a campus map, search locations, and compute the shortest route between two points using the **A* Search Algorithm**.

The application parses OpenStreetMap (.osm) files, builds a graph representation of the road network, and visualizes the map using HTML5 Canvas. Users can interact with the map through zooming, panning, searching, and route generation.

---

# ✨ Features

* 🗺️ Interactive OpenStreetMap visualization
* 📂 Upload custom `.osm` files
* 🔍 Local location search
* 🌍 Online search using OpenStreetMap Nominatim API
* 📍 Select source and destination points
* 🧭 Shortest path computation using A* Search
* 📏 Route distance calculation using the Haversine Formula
* 🔎 Smooth zoom and pan functionality
* 🏢 Dynamic rendering of buildings, roads, parks, and water bodies
* 📍 Automatic nearest-node detection for accurate routing

---

# 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)
* Tailwind CSS
* HTML5 Canvas API

### Data Source

* OpenStreetMap (OSM)

### APIs

* OpenStreetMap Nominatim API

---

# 🧠 Algorithms Used

### A* Search Algorithm

Computes the shortest path between the selected source and destination nodes using heuristic-based graph search.

### Haversine Formula

Calculates the geographical distance between two latitude-longitude coordinates for route distance estimation.

### Nearest Node Search

Finds the closest graph node corresponding to the selected location before executing the A* algorithm.

---

# 📂 Data Structures Used

* Graph (Adjacency List)
* Map
* Set
* Arrays
* Objects

---

# ⚙️ Project Workflow

```
Load OSM File
        │
        ▼
Parse XML Data
        │
        ▼
Build Graph
        │
        ▼
Render Interactive Map
        │
        ▼
Search / Select Locations
        │
        ▼
Find Nearest Nodes
        │
        ▼
Run A* Search
        │
        ▼
Display Shortest Path
        │
        ▼
Calculate Route Distance
```

---

# 📁 Repository Structure

```
Interactive-Campus-Navigation-System/
│
├── index.html
├── map.osm
├── demo.gif
├── home.png
└── README.md
```

---

# 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/Interactive-Campus-Navigation-System.git
```

### Run the Project

Open `index.html` in your browser.

For the best experience, run the project using the **Live Server** extension in Visual Studio Code.

---

# 📖 How to Use

1. Open the application.
2. Load the default map or upload your own `.osm` file.
3. Search for a location or click directly on the map.
4. Select the **Start** point.
5. Select the **Destination** point.
6. The application computes the shortest route using the A* Search Algorithm.
7. View the generated route and total travel distance.

---

# 📚 What I Learned

During this project, I gained practical experience in:

* Graph data structures
* A* Search Algorithm
* Geographic coordinate systems
* OpenStreetMap data parsing
* XML processing
* HTML5 Canvas rendering
* JavaScript event handling
* API integration
* Interactive web application development

---

# 🔮 Future Improvements

* Binary Heap based Priority Queue for faster A* execution
* KD-Tree / Quadtree for efficient nearest-node lookup
* Turn-by-turn navigation
* Multiple route suggestions
* Traffic-aware path planning
* User location support
* Improved mobile responsiveness
* Dark mode

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you find a bug or have an idea to improve the project, feel free to open an Issue or submit a Pull Request.

---

# 📄 License

This project is developed for educational and learning purposes.

---

# 👨‍💻 Author

**Sahil Verma**

* GitHub: https://github.com/sahilvermahr16-cmyk
* LinkedIn: https://www.linkedin.com/in/sahil-verma-990001319/
