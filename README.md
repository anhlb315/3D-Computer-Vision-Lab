# 3D Computer Vision Lab

Practical exercises for the 3D Computer Vision course.

## Project Structure

```
3D-Computer-Vision-Lab/
├── README.md
└── exercise_01/
    ├── data/
    ├── exercise_01.ipynb
    ├── output/
    └── requirements.txt
```

## Getting Started

### Step 1: Clone the repository and enter the exercise folder

```bash
git clone https://github.com/anhlb315/3D-Computer-Vision-Lab.git
cd 3D-Computer-Vision-Lab/exercise_01
```

### Step 2: Create a virtual environment (venv)

macOS / Linux:

```bash
python3 -m venv venv
```

Windows (CMD):

```cmd
python -m venv venv
```

### Step 3: Activate the virtual environment

macOS / Linux:

```bash
source venv/bin/activate
```

Windows (CMD):

```cmd
venv\Scripts\activate.bat
```

Windows (PowerShell):

```powershell
venv\Scripts\Activate.ps1
```

You should see `(venv)` at the beginning of your terminal prompt once it is activated.

### Step 4: Install dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### Step 5: Launch JupyterLab

```bash
jupyter lab
```

Your browser will open automatically at `http://localhost:8888`. If it does not, copy the URL containing the `token` from the terminal and paste it into your browser.

### Step 6: Shut down

- Stop JupyterLab: press `Ctrl + C` in the terminal, type `y`, then press Enter.
- Leave the virtual environment:

```bash
deactivate
```

## Running Again Later

```bash
cd 3D-Computer-Vision-Lab/exercise_01
source venv/bin/activate        # Windows CMD: venv\Scripts\activate.bat
jupyter lab
```

## Notes

- Always run `jupyter lab` from inside the `exercise_01` folder so that relative paths to `data/` work correctly.
