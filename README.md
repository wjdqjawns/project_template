# project_template
General-purpose project folder structure for robotics, aerospace, and research & engineering projects.  
This repository is intended to be used as a **template**.  
Create a new repository using **"Use this template"** to start a new project.


## Folder Structure Overview

```
project/
├── archive/
├── documents/
├── experiments/
├── hardware/
├── simulation/
└── software/
```

Each top-level directory has a clear responsibility to keep projects structured, reproducible, and scalable.


## archive/
- Archived or deprecated files, old versions, and unused materials.
- Used to keep the main project clean while preserving history.


## documents/
All **human-readable project documents**.

```
documents/
├── agreements/
├── development/
├── outputs/
└── reviews/
```


### agreements/
Contracts, NDAs, MOUs, and administrative documents.

### development/
Project-wide technical documents that define **how the system is built**.

```
development/
├── 00_schedule/
├── 01_requirements/
├── 02_design/
├── 03_procedures/
├── 04_references/
└── 05_research_notes/
```

#### 00_schedule/
Project schedule, milestones, timeline, and planning spreadsheets.

#### 01_requirements/
System, functional, performance, and interface requirements.

#### 02_design/
System architecture, hardware/software design, control design, and technical solutions.

#### 03_procedures/
Reusable procedures:
- development procedures  
- assembly procedures  
- test procedures  

(Experiment-specific procedures belong in the experiment folder.)

#### 04_references/
External references:

```
datasheets/ - component specifications
manuals/ - tool, framework, or equipment manuals
papers/ - academic papers and technical documents
standards/ - official standards and regulations
```

#### 05_research_notes/
Informal notes, ideas, calculations, and early-stage thoughts.

### outputs/
Final project deliverables.

```
outputs/
├── demo/ # demo videos, screenshots, showcase material
├── figures/ # final figures for papers/presentations
├── papers/
├── posters/
├── presentations/
└── reports/
```

Only polished and externally shareable materials belong here.

### reviews/
Formal project reviews and evaluations.

```
reviews/
├── proposal/
├── progress/
└── final/
```
Examples: SRR, PDR, CDR, midterm reports, final reviews.


## experiments/
Each experiment is stored as an independent, reproducible unit.

```
experiments/[YYYYMMDD]_exp_name/
├── 00_documents/
├── 01_data_raw/
├── 02_data_processed/
├── 03_figures/
└── 04_results/
```

- `00_documents` : procedures, configuration, signed reports  
- `01_data_raw` : raw measurements  
- `02_data_processed` : filtered/processed data  
- `03_figures` : experiment-specific plots  
- `04_results` : final outputs  


## hardware/
All hardware design and manufacturing files.

```
hardware/
├── cad/ # CAD models, STEP, STL
├── ecad/ # schematics, PCB design
└── fabrication/ # manufacturing files, drawings, BOM
```


## simulation/

Simulation projects with the same structure as experiments.

```
simulation/simulation_name/
├── 00_documents/
├── 01_data_raw/
├── 02_data_processed/
├── 03_figures/
└── 04_results/
```


## software/

Source code and software projects.

Structure is project-dependent.


## Notes

- Empty folders contain `.gitkeep` to preserve structure in Git.
- Large datasets should be excluded using `.gitignore`.
- This structure is designed to scale from small research projects to large system development.


## Usage

1. Click **Use this template** on GitHub.
2. Create a new repository.
3. Clone it locally.
4. Start working.


## License

Specify if needed.