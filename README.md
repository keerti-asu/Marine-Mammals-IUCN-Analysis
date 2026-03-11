# Marine Mammals Taxonomy & IUCN Red List Analysis

## Introduction
This project focuses on the taxonomy and conservation status of 187 species of marine mammals. Using the **IUCN Red List of Threatened Species**, this analysis categorizes species based on their risk of extinction, ranging from "Data Deficient" to "Extinct".

## Project Objectives
- Organize marine mammal taxonomy (Kingdom, Phylum, Class, Order, Family, Genus, Species).
- Clean and process raw data into a relational database format.
- Analyze the distribution of threatened species (Vulnerable, Endangered, Critically Endangered) per family.
  <img width="1068" height="688" alt="image" src="https://github.com/user-attachments/assets/8c3d5bae-3bb9-44e5-b9bf-d7f2f6e711ed" />


## Database Schema
The project implements a relational schema including the following tables:
- **Kingdom, Phylum, Class, Order, Family, Genus**
- **Species**: Contains `taxonID`, `sName`, `friendlyName`, and `category`.
- **SpCountry**: Maps species to their geographical occurrence.

## Installation & Usage
1. Clone the repository.
2. Ensure you have `pandas`, `numpy`, and `matplotlib` installed.
3. Run the provided Jupyter Notebook or Python script to process the `IUCNHierarchyAndExtinction.csv` data.

## Author
Keerti Upadhyay
