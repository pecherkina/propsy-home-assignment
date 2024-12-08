# Functional MRI data visualization - PTSD
<em>Programming for Psychologists 2024/25 (Vrije Universiteit Amsterdam). Home assignment.</em>

**Course code:** M_PROPSY\
**Student:** Anna Pecherkina\
**Course coordinator:** Matthias Nau\
**Teaching assistant:** Anna van Harmelen

## Description
The current project provides a flexible tool for visualizing brain activity related to any psychological concept from the [Neurosynth database](https://neurosynth.org/analyses/terms/).

This Jupyter Notebook demonstrates analysis of fMRI PTSD data. The notebook generates two informative figures: the first overlays functional data onto anatomical brain scans to pinpoint areas strongly linked to the PTSD, while the second displays a histogram of voxel intensities for a detailed view of brain activity.

## Installation
Instructions on how to set up and install the project. This includes requirements, dependencies, and a step-by-step guide.

### Used data
Data from the [Neurosynth database](https://neurosynth.org/analyses/terms/) 

### Requirements
- Python 3 (e.g., Python 3.12.7)
- Libraries: matplotlib, nibabel, nilearn 
- Jupyter Notebook

### Setup
1. **Clone the repository**
```bash
  git clone https://github.com/pecherkina/propsy-home-assignment.git
```
2. **Install dependencies**
```bash
pip install matplotlib nibabel nilearn 
```

## Features
- Visualization of brain regions associated with psychological concepts.
- Histogram display of voxel intensities.
- Customizable data exploration for different psychological concepts.