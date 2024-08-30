# Pandemic Simulation Project

## Overview
This project was my final university assignment, focusing on working with SI-, SIS-, and SIR- models, enhanced with Pandemic graph and model logic. The goal was to observe how different models behave and find optimal solutions for curbing infections and stopping a global pandemic.

## Project Structure and Contents

### Main Folder:

#### Files:
- `Pandemic.ipynb`: Demonstrates the creation of the pandemic graph
- `Math.ipynb`: Explains the mathematics behind the SI-, SIS-, SIR- models
- `Infections.ipynb`: First iteration of infections on the Pandemic graph with one virus
- `Disinfect.ipynb`: The initial cure mechanism
- `1Virus.ipynb`: All components combined without the fancy graphs of the previous files
- `cities_cords.tsv`: Coordinates for graph creation
- `cities.csv`: Data for the cities of the pandemic graph

#### Subfolders:

1. **Test**
   - `combined_SUMStats`: Contains diagrams for every tested step with different setups

2. **SIPandemic**
   - Notebooks showing the dynamics of SI, SIS, and SIR models on the pandemic graph for optimal comparison

3. **SI-ModelsPandemic**
   - Similar to SIPandemic but with more iterations (up to 10,000)

4. **OneDisease**
   - Pandemic model with a single disease, without cure, showcasing all possible setups

5. **Cure**
   - **OneDisease**: 
     - CSV files similar to previous folders
     - `CureOneColor.ipynb`: Creates CSV files for the blue color
     - `CureRed.ipynb`, `CureYellow.ipynb`, `CureBlack.ipynb`: Create CSV files for other colors
     - `CompareCureOneColor.ipynb`: Compares CSV files of different cures with only one disease
   - **4Diseases**:
     - Similar to OneDisease, but with notebooks for CSV creation and comparisons for four diseases

6. **CSV-Files**
   - Notebooks to verify CSV creation

7. **4Diseases** and **4Diseases10k**
   - Create CSV files without a cure but with 4 diseases instead of one

## How to Run
All notebooks work with Google Colab. To test on your Google Drive:
1. Adjust the folder structure as needed
2. Upload the required CSV files (like cities.csv) to your working folder

Note: For actual simulations, some CSV files are 1GB or larger. Due to their size, they're not included in the repository.

## Accessing Large CSV Files
If you need the large CSV files for simulations, please contact me via email. These files have filled up my 100GB Google Drive storage.

## Usage Instructions
1. Open the desired notebook with Google Colab
2. Adjust file paths if necessary
3. Run the cells to see all diagrams and graphs

## Screenshots
![Application Screenshot](screenshots/Pandemi1.png)
![Application Screenshot](screenshots/Pandemi2.png)
![Application Screenshot](screenshots/Pandemi3.png)

## Future Development
This project is currently complete. However, feel free to fork and expand upon the work if interested.

## Contact
For questions or to request large CSV files, please contact me at [dominik.urban1@gmx.de].

