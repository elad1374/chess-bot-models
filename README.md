# Chess Bot Trained Models & Weights

This repository contains the pre-trained weights and models for the **Chess-Bot** project.  

---

## Setup & Installation

To run the main chess robot application, download the models from this repository and place them inside the `chess-bot/runs` directory of the main project.

### 1. Prerequisites (Git LFS)
Ensure **Git LFS** is installed before cloning (required to download the actual model weights):
```bash
git lfs install
```

### 2. Clone this Repository
Download or clone repository to your local machine:
```bash
git clone https://github.com/elad1374/chess-bot-models.git
```

### 3. Copy Models to Main Project
Copy from `../chess-models/` the **entire folders** (`classify`, `detect`, `pose`) into your main project's `runs` directory:
```bash
# Example structure:
chess-bot/
├── runs/                <-- Place the downloaded model folders here
│   ├── classify/
│   ├── detect/
│   └── pose/
└── src/
```