# navygit.github.io

How to use this ChEMBL App ?

Open https://navygit.github.io/   

or

1. Fire up the index.html file in your favorite browser

2. Go to Static > Data folder

3. Use those examples:  input.txt --> load the molecule 3-d structure ; fail_input.txt and input.smi fail to open

Application Specifications :

Your task is to create a simple JavaScript web application.

Initially, the application should have a drag and drop area as its only visual component. The drag and drop area should accept text files. Normally a text file should contain a single line with a single string, the applicaiton should indicate an error if that's not the case. The example content of a valid file: O=C(Oc1ccccc1C(=O)O)C This string is called SMILES (Simplified molecular-input line-entry system) string, and it descibes a structure of a chemical compound. As a result of this part your application should print the content of the valid file to the console.

After receiving a valid file, the application should use the ChEMBL API methods to convert SMILES string from the file to xyz coordinates. As a result of this part your application should print the xyz coordinates obtained from the API for the corresponsing SMILES.

Having the coordinates, the application should use the Speck library (source: https://github.com/wwwtyro/speck) to display a 3D compound model.

The applicaiton should be stored in a public GitHub repository and deployed as a github pages of this repository.
