# Geometry Volume App

## Project Description

This app simulates a simple geometry volume calculator. The app supports calculation of volumes for spheres, cylinders, cones, and rectangular boxes using mathematical formulas.

## Project Structure Explanation

```
geometry-volume-app/
├── main.py                # Main app
├── requirements.txt       # App dependencies
├── README.md              # Project documentation
├── geometry/              # Geometry calculation modules
│   ├── __init__.py
│   ├── sphere.py          
│   ├── cylinder.py        
│   ├── cone.py            
│   └── box.py             
└── tests/                 # Unit tests
    ├── __init__.py
    ├── test_sphere.py
    ├── test_cylinder.py
    ├── test_cone.py
    └── test_box.py
```

## How to Run main.py

Execute the app using:

```bash
python main.py
```

This will launch a menu where you can select a shape and input the dimensions to calculate its volume.

## How to Run Tests

Run all tests using pytest:

```bash
pytest
```

## Dependencies

The project requires the following dependencies:

- **pytest** (9.0.2) - Testing framework
- **colorama** (0.4.6) - Colored terminal output
- **packaging** (26.0) - Package versioning utilities
- **pluggy** (1.6.0) - Plugin system for pytest
- **iniconfig** (2.3.0) - Configuration file parsing
- **Pygments** (2.19.2) - Syntax highlighting

Install all dependencies using:

```bash
pip install -r requirements.txt
```