# BIOMD0000000148: Komarova2003_BoneRemodeling

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000148.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000148.git@20140916`


# Model Notes


This a model from the article:  
** Mathematical model predicts a critical role for osteoclast autocrine regulation in the control of bone remodeling.**   
Komarova SV, Smith RJ, Dixon SJ, Sims SM, Wahl LM _Bone_2003 Aug;33(2):206-15
[14499354](http://www.ncbi.nlm.nih.gov/pubmed/14499354),  
**Abstract:**   
Bone remodeling occurs asynchronously at multiple sites in the adult skeleton
and involves resorption by osteoclasts, followed by formation of new bone by
osteoblasts. Disruptions in bone remodeling contribute to the pathogenesis of
disorderssuch as osteoporosis, osteoarthritis, and Paget's disease.
Interactions among cells of osteoblast and osteoclast lineages are critical in
the regulation of bone remodeling. We constructed a mathematical model of
autocrine and paracrine interactions among osteoblasts and osteoclasts that
allowed us to calculate cell population dynamics and changes in bone mass at a
discrete site of bone remodeling. Themodel predicted different modes of
dynamic behavior: a single remodeling cycle in response to an external
stimulus, a series of internally regulated cycles of bone remodeling, or
unstable behavior similar to pathological bone remodeling in Paget's disease.
Parametric analysis demonstrated that the mode of dynamic behaviorin the
system depends strongly on the regulation of osteoclasts by autocrine factors,
such as transforming growth factor beta. Moreover, simulations
demonstratedthat nonlinear dynamics of the system may explain the differing
effects of immunosuppressants on bone remodeling in vitro and in vivo. In
conclusion, the mathematical model revealed that interactions among
osteoblasts and osteoclasts result in complex, nonlinear system behavior,
which cannot be deduced from studies of each cell type alone. The model will
be useful in future studies assessing the impact of cytokines, growth factors,
and potential therapies on the overall process ofremodeling in normal bone and
in pathological conditions such as osteoporosis and Paget's disease.

The model reproduces Fig 2A and Fig 2B of the paper. Note that the Y-axis
scale is not right, the osteoblast steadystate is approximatley 212 and not 0
as depicted in the figure. Also, there is atypo in the equation for x2_bar
which has been corrected here. Model successfully tested on MathSBML.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


