# Montecarlo-simulation

This project tries to reproduce the stellar population of the Milky Way using Montecarlo simulations. The focus is on modeling distributions of main sequence stars and stellar remnants (white dwarfs, neutron stars, and black holes) by sampling from Kroupa's Initial Mass Function (IMF). Five samples of varying sizes are used to predict the galaxy's stellar mass and remnant distributions.

## Project Structure
- `MONTECARLO OF FINAL.ipynb`: Jupyter Notebook with Python code implementing the Montecarlo simulation, stellar mass sampling and classification.
- `Montecarlo_CatalinaRiveros.pdf`: Paper detailing the methods, equations, and results of the simulation, including visualizations of mass and age distributions for each stellar remnant type.

## Key Features
- **Stellar Sampling:** Generates random samples of stars based on Kroupa's IMF.
- **Stellar Classification:** Classifies stars as main sequence or remnants (white dwarfs, neutron stars, black holes) based on their initial masses.
- **Mass and Age Distribution:** Computes distributions of stellar mass and age to represent the Milky Way's stellar population.
- **Data Visualization:** Displays mass distribution, remnant classification, and age distribution graphs.

## Usage
Open the Jupyter Notebook:
**jupyter notebook "MONTECARLO OF FINAL.ipynb"**
Run each cell in sequence to perform the simulation.

## Methodology
The python code follows these main steps:

1. Stellar Sampling: Five samples are generated with sizes ranging from 100 to 1,000,000 stars.
2. Initial Mass Function: Stars are distributed according to Kroupa's IMF.
3. Remnant Classification: Stars are classified into main sequence, white dwarfs, neutron stars, and black holes.
4. Final Mass Calculation: Final masses for remnants are computed using equations for each remnant type.

##Results
Key findings include:
- Approximately 70% of stars in each sample remain on the main sequence.
- White dwarfs are the most common stellar remnant due to the prevalence of low-mass stars.
- Larger samples provide a closer approximation to observed stellar populations.

## Contact
For questions, contact Catalina Riveros-Jara at catalina.riverosj@usm.cl.
