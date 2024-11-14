# Bend-aid Overview

[![arXiv](https://img.shields.io/badge/Actuators-Paper-blue)](https://doi.org/10.3390/act1010000)

The Bend-aid visual interface developed for using with [**TorqueTuner**](https://www.idmil.org/project/the-torquetuner-hub/) is affiliated with the latest journal article published in Actuators titled: Assessing the Impact of Force Feedback in Musical Knobs on Performance and User Experience.

Piao, Z.; Frisson, C.; Van Kerrebroeck, B.; Wanderley, M.M. Assessing the Impact of Force Feedback in Musical Knobs on Performance and User Experience. *Actuators* 2024, 1, 0. [https://doi.org/10.3390/act1010000](https://doi.org/10.3390/act1010000)

![Bend-aid UI Interface](https://github.com/piaoziyue/Bend-aid-Actuators-2024/blob/main/Bend-aid-ui.png)
## Key functions

- Pitch Modulation via TorqueTuner: Allows users to synthesize vibrato by controlling pitch through the rotation of the TorqueTuner knob, providing customizable force feedback modes.
- MIDI Sequencer Integration:
    - Add, highlight, move, and resize notes intuitively.
    - Supports editing a wide range of notes and importing, clearing, or manually entering note data.
- TorqueTuner Visualizer:
    - Real-time monitoring of rotation angle and torque value.
    - Displays angle contour aligned with MIDI notes and allows saving pitch contour data as a CSV file.
- Data Communication:
    - Real-time data exchange between TorqueTuner and Bend-aid via USB.
    - Supports pitch modulation and mode adjustments with feedback displayed on both the Bend-aid interface and TorqueTuner's LCD.

## Installation Guide

To set up the software environment, follow these steps:

1. **Clone the repository from GitHub**:
    ```bash
    git clone https://github.com/piaoziyue/Bend-aid-Actuators-2024.git
    ```

2. **Upload Firmware to TorqueTuner**:  
   Upload the `TorqueTuner_ESP32` code to your TorqueTuner device using the appropriate tool.

3. **Open the Web Interface**:  
   Open `index.html` in your browser using Live Server or a similar local web hosting tool.

4. **Connect TorqueTuner to Bend-aid**:  
   Connect the TorqueTuner device to the Bend-aid system for real-time interaction.

## Citation

```
@article{piao2024impact,
  author    = {Ziyue Piao and Christian Frisson and Bavo Van Kerrebroeck and Marcelo M. Wanderley},
  title     = {Assessing the Impact of Force Feedback in Musical Knobs on Performance and User Experience},
  journal   = {Actuators},
  year      = {2024},
  volume    = {1},
  pages     = {0},
  doi       = {10.3390/act1010000},
  url       = {https://doi.org/10.3390/act1010000}
}
```

## Contact

Ziyue Piao (PhD candidate in Music Technology at IDMIL, MPBL, CIRMMT, McGill University)
ziyue.piao@mail.mcgill.ca

Nov. 12, 2024


## Copyright 
© 2024 by the authors. Licensee MDPI, Basel, Switzerland. This article is an open access article distributed under the terms and conditions of the Creative Commons Attribution (CC BY) license (https://creativecommons.org/licenses/by/4.0/)

