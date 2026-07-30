# 🗺️ Interactive Campus Navigation System using A* Search and OpenStreetMap

An interactive web-based campus navigation system that visualizes OpenStreetMap (OSM) data, enables users to search locations, select source and destination points, and computes the shortest route using the **A\* Search Algorithm**. The application is built using **HTML5 Canvas**, **JavaScript**, and **OpenStreetMap**, providing an intuitive and responsive map exploration experience.

---

## 📌 Project Overview

Finding the shortest path inside a large campus can be challenging, especially for new students and visitors. This project provides a smart navigation system that allows users to:

- Load OpenStreetMap (.osm) files
- Visualize campus roads, buildings, parks, and water bodies
- Search locations locally and online
- Select start and destination points
- Compute the shortest route using the A* Search Algorithm
- Display the total travel distance
- Navigate through the map using zoom and pan controls

---

# 🚀 Features

### 🗺️ Interactive Map Visualization
- Render OpenStreetMap (.osm) data on HTML5 Canvas
- Display roads, buildings, parks, and water bodies
- Dynamic map rendering with smooth interactions

### 📂 OSM File Loader
- Upload any custom `.osm` file
- Load a default map instantly

### 📍 Smart Location Search
- Local search using loaded OSM data
- Online search using OpenStreetMap Nominatim API

### 🧭 Shortest Path Navigation
- Select start and destination nodes
- Compute shortest path using A* Search
- Display shortest route visually on the map

### 📏 Distance Calculation
- Calculates total route distance
- Uses the Haversine Formula for accurate geographic distance

### 🔍 Interactive Controls
- Mouse wheel zoom
- Drag to pan
- Double-click to zoom
- Reset map view

### 📌 Dynamic Labels
- Campus name
- Building names
- Road names
- Labels appear according to zoom level

---

# 🛠️ Tech Stack

## Frontend
- HTML5
- CSS3
- JavaScript (ES6)
- Tailwind CSS
- HTML5 Canvas API

## Data Source
- OpenStreetMap (.osm)

## APIs
- OpenStreetMap Nominatim API

---

# 🧠 Algorithms Used

## A* Search Algorithm
Used to compute the shortest path between the selected source and destination nodes.

### Why A*?
- Fast shortest path computation
- Uses heuristic-based search
- More efficient than Dijkstra for point-to-point navigation

---

## Haversine Distance Formula

Used to calculate the geographical distance between two latitude-longitude coordinates.

Applications:
- Edge cost calculation
- Route distance measurement
- A* heuristic estimation

---

## Nearest Node Search

Converts the user-selected location into the nearest graph node before running the A* algorithm.

---

# 📂 Data Structures Used

- Graph (Adjacency List)
- Map
- Set
- Arrays
- Objects

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
Render Map
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
Calculate Total Distance
```

---

# 📁 Project Structure

```
Interactive-Campus-Navigation-System/
│
├── index.html          # Main application
├── map.osm             # Default OpenStreetMap file
├── README.md
```

---

# ▶️ Getting Started

## Clone Repository

```bash
git clone https://github.com/your-username/Interactive-Campus-Navigation-System.git
```

## Open Project

Simply open:

```
index.html
```

in your browser.

Or use **Live Server** in Visual Studio Code for the best experience.

---

# 🎯 How to Use

1. Open the application.
2. Load the default map or upload your own `.osm` file.
3. Search for a location or click directly on the map.
4. Select the **start point**.
5. Select the **destination**.
6. The application computes and displays the shortest route.
7. View the total distance traveled.

---

# 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Graph data structures
- A* Search Algorithm
- Pathfinding algorithms
- Geographic coordinate systems
- OpenStreetMap data parsing
- XML processing
- HTML5 Canvas rendering
- JavaScript event handling
- API integration
- Interactive UI development

---

# 🔮 Future Improvements

- Priority Queue implementation for faster A* search
- KD-Tree / Quadtree for efficient nearest node lookup
- Turn-by-turn navigation
- Multiple route alternatives
- Traffic-aware routing
- User location tracking
- Mobile responsiveness
- Dark mode support

---

# 📸 Screenshots

> Add screenshots or GIFs here.

```
Home Screen

Map Visualization

Shortest Path

Search Feature
```

---

# 📄 License

This project is intended for educational and learning purposes.

---

# 👨‍💻 Author

**Sahil Verma**

- GitHub: https://github.com/sahilvermahr16-cmyk
- LinkedIn: https://www.linkedin.com/in/sahil-verma-990001319/
