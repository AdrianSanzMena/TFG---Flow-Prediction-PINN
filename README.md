**USO DE REDES NEURONALES FÍSICAMENTE INFORMADAS
(PINN) EN LA INGENIERÍA AEROESPACIAL | USE OF PHYSICS INFORMED NEURAL NETWORKS (PINN) IN
AEROSPACE ENGINEERING**  

This repository contains all the necessary code and resources created for my Final Degree Project "USE OF PHYSICS INFORMED NEURAL NETWORKS (PINN) IN
AEROSPACE ENGINEERING" for the Universidad de León.  

**Project Overview:**  
This project uses PINN for prediction of incompressible flow in different scenarios:
  - Free Flow
  - Poiseuille Flow
  - Boundary Layer and Solid Boundaries Effect
  - Flow Around a Non-Lifting Cylinder
  - Flow Around a NACA Airfoil
Several technical approaches have been used, some based on other author's work and some other of my own.

**Repository Structure:**  
All the necessary code is organized in different jupyter notebooks with easy to identify names.
  - Notebooks: Main codes in ".ipynb" format. All the code is prepared to be fully run automatically by clicking the "play" button present in ".ipynb" files. 
  - Requirements.txt: List of requirements*
  - LICENSE: CC BY-NC 4.0 License.
  - REFERENCES.pdf: Contains all the references used for the development of this project.

**Requirements:**  
This project uses a Python virtual environment (not conda). To reproduce the results:  
```bash
  python3 -m venv venv
  source venv/bin/activate
  pip install -r requirements.txt
```

**DISCLAIMER:** All the code in this repository is mainly executed in GPU to take advantage of the CUDA acceleration. However, it can be changed by changing the variable 
```device = 'CUDA'```
 to 
```device = 'CPU'```
 present in every notebook if desired.

**AUTHOR:**  
Adrián Sanz Mena  
E-mail: asanzm03@estudiantes.unileon.es  
Personal E-mail: adriansanz712@gmail.com  
LinkedIn: linkedin.com/in/adrian-sanz-mena-0817a6344
