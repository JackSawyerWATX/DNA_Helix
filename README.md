# DNA Helix Visualization

A 3D visualization of a DNA double helix structure using Python and vedo.

## Description

This project creates an interactive 3D rendering of a DNA double helix. The visualization displays:
- Two helical strands colored red and blue
- White connector bars between the strands representing base pair bonds
- Smooth, parametric curves forming the characteristic DNA helix shape

## Requirements

- Python 3.7+
- numpy
- vedo
- vtk
- matplotlib

## Installation

1. Clone the repository:
```bash
git clone https://github.com/JackSawyerWATX/DNA_Helix.git
cd DNA_Helix
```

2. Create a virtual environment (recommended):
```bash
python -m venv .venv
.venv\Scripts\activate  # On Windows
# source .venv/bin/activate  # On macOS/Linux
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

Or install individually:
```bash
pip install numpy vedo
```

## Usage

Run the visualization:
```bash
python main.py
```

An interactive 3D window will open. You can:
- Rotate the view by clicking and dragging
- Zoom in/out with the mouse wheel
- Interact with the visualization as enabled by vedo

## How It Works

The script uses parametric equations to create two interlocking helical curves:
- Both strands follow similar helical paths but are offset by π (180°)
- The strands are rendered as tubes with a specified radius
- Connector bars are drawn at regular intervals to show base pair interactions
- The black background and 3D axes provide spatial context

## Files

- `main.py` - Main visualization script
- `README.md` - This file

## License

MIT License - Feel free to use and modify this code

## Author

Jack Sawyer
