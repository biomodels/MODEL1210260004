# MODEL1210260004: MODEL

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1210260004.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1210260004.git@20140916`

## Usage

Importing the model package.

`import MODEL1210260004 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes

    
    
    "Modeling the Role of Peroxisome Proliferator-Activated Receptor γ and MicroRNA-146 in Mucosal Immune Responses to Clostridium difficile"
    
    Monica Viladomiu1,2, Raquel Hontecillas1,2, Mireia Pedragosa1,2, Adria Carbo1,2, Stefan Hoops1,2, Pawel Michalak4,5, Katarzyna Michalak4, Richard L. Guerrant2,3, James K. Roche2,3, Cirle A. Warren2,3, Josep Bassaganya-Riera1,2*
    
    1) Nutritional Immunology and Molecular Medicine Laboratory, Virginia Bioinformatics Institute, Virginia Tech, Blacksburg, Virginia, United States of America, 2) Center for Modeling Immunity to Enteric Pathogens, Virginia Tech, Blacksburg, Virginia, United States of America, 3) Division of Infectious Disease and International Health, Center for Global Health, University of Virginia, Charlottesville, Virginia, United States of America, 4) Medical Informatics and Systems Division, Virginia Bioinformatics Institute, Virginia Tech, Blacksburg, Virginia, United States of America, 5) Department of Biological Sciences, Virginia Tech, Blacksburg, Virginia, United States of America
    
    E-mail: jbassaga@vt.edu
    
    This model represents the interaction between Cdiff, miRNA146b, NCOA4, PPARg, IL10 and IL17. Simulation studies show an aberrant expression of miRNA146b with increasing concentrations of Cdiff over time, which results in decreased PPARg activation due to NCOA4 inhibition. As a final result, PPARg is unable to modulate effector and regulatory responses, since results show an upregulation of IL17 expression and downregulation of IL10 production.


