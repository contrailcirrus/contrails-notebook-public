# Contrail Region Structure (Part I)

> Analysis for the post [Contrail Region Structure (Part I): The thickness of persistent contrail regions](https://notebook.contrails.org/contrail-region-structure-part-i/))

## Overview

This repository contains scripts for processing and analyzing [GRUAN](https://www.gruan.org/) radiosonde and waypoint data.

## Folder Contents

### Main Folders
- `gruan/`: Contains scripts for GRUAN radiosonde data processing.
  - `gruan_analyze_processed_files.py`: Analyzes processed GRUAN files.
  - `gruan_peek_nc.py`: Inspects GRUAN NetCDF files.
  - `gruan_process_raw.py`: Processes raw GRUAN data.
  - `gruan_web_scrape_cloud.py`: Cloud-compatible GRUAN web scraping.
  - `gruan_web_scrape_raw.py`: Scrapes raw GRUAN data from the web.

- `thermo/`: Contains thermodynamic calculation scripts.
  - `contrail_thermo.py`: Functions for contrail-related thermodynamic calculations.
  - `flight_level_conversion.py`: Converts between pressure and flight levels.

- `iagos/`: Contains scripts for IAGOS waypoint data processing.
  - `iagos_analyze_processed_waypoints.py`: Analyzes processed waypoint data.
  - `iagos_process_waypoints.py`: Processes IAGOS waypoint data.

### Configuration Files
- `.pre-commit-config.yaml`: Configures pre-commit hooks for code quality.
- `requirements.txt`: Lists Python dependencies.
- `environment.yml`: Conda environment configuration.

### Documentation
- `README.md`: Provides an overview of the repository.

### Notebooks
- `google_cloud_setup.ipynb`: Jupyter notebook for setting up Google Cloud.

## Usage
Refer to individual scripts for specific functionality and usage instructions.
