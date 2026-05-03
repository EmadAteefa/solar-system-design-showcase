# Solar System Design Web Application

A full-stack web application for designing solar energy systems, calculating electrical loads, selecting compatible components, and reviewing project analysis dashboards.

## Overview

The application turns a solar system design workflow into an interactive web experience. It supports electrical load calculation, PV/inverter/battery selection, system validation, cost summaries, and engineering dashboards through a clean bilingual interface.

## Features

- Multi-step solar design workflow.
- Single-phase and three-phase load calculations.
- Automatic and manual component selection.
- PV, inverter, and battery compatibility checks.
- Cost and quotation summary.
- BOM dashboard.
- Feasibility dashboard.
- PV simulation dashboard.
- System diagram dashboard.
- Arabic RTL and English interface support.
- Responsive layout for desktop and mobile screens.

## Tech Stack

- Python
- Flask
- SQLite
- HTML
- CSS
- JavaScript
- Bootstrap
- Jinja templates
- PDF report generation

## Architecture

```mermaid
flowchart LR
    User["User"] --> UI["Web Interface"]
    UI --> API["Flask API"]
    API --> Services["Calculation and Analysis Services"]
    API --> Data["Component Data"]
    Services --> Results["Design Results"]
    Data --> Results
    Results --> UI
```

## Screenshots

### Home

![Home](screenshots/home.png)

### Design Setup

![Design Setup](screenshots/design-setup.png)

### Component Selection

![Component Selection](screenshots/component-selection.png)

### Design Results

![Design Results](screenshots/design-results.png)
