# Alzheimer-Model-App
This repository contains the computational pipeline developed for the simulation and analysis of brain dynamics associated with Alzheimer’s disease progression.  The project integrates structural connectivity, neural mass modeling, simulated M/EEG signals, feature extraction, and machine learning classification.

1. Pipeline Overview

  The workflow includes:
  1. Structural connectivity generation (MRtrix3 + DTI)
  2. Atlas alignment and connectome construction
  3. Wilson-Cowan neural modeling
  4. Simulated M/EEG signal generation
  5. Spectral and connectivity biomarker extraction
  6. Machine learning classification
  7. Clinical decision support interface

2. Repository Structure

  2.1 procesamiento_python
  Scripts for individual patient processing:
  
  - Atlas alignment and correction
  - Structural connectivity generation
  - Wilson-cowan model calibration
  - Neural activity simulation
  - Simulated M/EEG generation
  - Visualization and parameter extraction
  
  2.2 procesamiento_grupal
  Group-level processing and model training:
  
  - Feature computation
  - Dataset construction
  - Neural network training
  - Clinical interface application

3. Data availability

MRI and diffusion imaging data are not included due to ADNI data usage restrictions and file size limitations.
Authorized researchers may reproduce the pipeline using their own ADNI dataset.

4. Requirements

Install dependencies with:
  pip install -r requirements.txt

5. Authors 

Javier Orlando Patiño Carranza
Laura Vanesa Beltran Suarez

Undergraduate Monograph - Systems Engineering
Colombia

6. License

This project is released for academic and research purposes


