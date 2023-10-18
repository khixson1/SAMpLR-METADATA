# SAMpLR-METADATA
This code takes as input Compound Name or Pubchem ID (CID) or CAS, or InChIKey. With at least one compound identifier, the script will perform webscraping of Pubchem, ChEBI, ChEMBL, Lipid MAPS and ClassyFire to retrieve other associated metadata for the defined compound. 

The script will display the user supplied ("Supplied"), parent ("Parent") which is the primary compound if supplied compound contains multiple components, and will return metadata on component compounds (e.g., salts, acids, water) in addition to parent compound if present.

This script was created and tested in Google's Colaboratory Python Notebook environment (https://colab.research.google.com) which is a Jupyter Notebook environment. WARNING: Script performance is dependent on operational Pubchem, ChEBI, ChEMBL, Lipid MAPS and ClassyFire websites.

**<h3>Retrieved Metadata Includes:</h3>**

**Pubchem Derived**
- Compound Name
- Synonyms
- Pubchem ID (CID)
- CAS
- IUPAC Name
- InChIKey
- InChI
- Canonical SMILES
- Isomeric SMILES
- Molecular Formula
- Molecular Weight
- Exact Mass
- Associated Organisms
  
**ChEBI Derived**
- ChEBI ID
- ChEBI IS Descriptor
- ChEBI Chemical Role
- ChEBI Biological Role
- ChEBI Application
- KEGG Compound ID
- KEGG Drug ID
- Drug Central ID
- Drug Bank ID
- ChemSpider ID
- MetaCyc ID
- Veterinary Substances Database (VSDB) ID
- Human Metabolome Database (HMDB) ID
- Lipid Maps ID
- Library of Integrated Network-based Cellular Signatures (LINCS) ID

**ClassyFire Derived**
- Kingdom
- Superclass
- Class
- Subclass
- Direct Parent
- Alternative Parents
- CHEMONTIDs
- CHEMONTID Names

**Lipid Maps Derived**
- Lipid Common_Name
- Lipid Abbreviations
- Lipid Map_ID
- LIPIDAT ID
- SWISSLIPIDS ID
- Lipid Category
- Lipid Main Class
- Lipid Subclass

**Pubchem & ChEMBL Physiochemical Parameters**
- ALogP3
- XLogP3	
- Aromatic Ring Count
- LogD at pH 7.4
- LogP
- Acidic pKa
- Basic pKa
- H-Bond Accptor Count
- H-Bond Accptor Lipinski
- H-Bond Donor Count
- H-Bond Donor (Lipinski)
- Heavy Atom Count
- Natural Product Likeness
- Ro5 Violations
- Polar Surface Area
- Molecular Volume
- QED (Weighted)
- Rotatable Bond Count
- Chirality
- Complexity
- Isotope Atom Count
- Defined Atom Sterocenter Count
- Undefined Atom Stereocenter Count
- Defined Bond Stereocenter Count
- Undefined Bond Stereocenter Count
- Formal Charge	Solubility [mg/L_at_18C]
- Density
- UV Spectra
- Collisional Cross Section [M+H]+
- Collisional Cross Section [M+K]+
- Collisional Cross Section [M+Na]+
- Collisional Cross Section [M-H]-
- Dissociation Constants
- Ro3 Pass
- Common Substructure
- Indication Class
- Target IDs
- Organism Targets
- Target Names
- Alert IDs
- Alert Names
- Alert Sets
- Alert Smarts
- Similar MW_Compounds
- Similar MW_Names
- Similar MW_MonoMW
- Similar Structure Compounds
- Similar Structure Name
- Similar Structure Similariy
- Mol File (2D)
- Mol File (3D)
- Coordinates (2D)
- Biotherapeutic

