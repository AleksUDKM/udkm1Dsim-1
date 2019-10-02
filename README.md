# udkm1Dsim

The udkm1Dsim toolbox is a collection of Python classes and routines 
to simulate the structural dynamics and the according X-ray 
diffraction response in one-dimensional sample structures after 
ultrafast excitation. 
The toolbox provides the capabilities to define arbitrary layered 
structures on the atomic level including a rich database of 
element-specific physical properties. 
The excitation of ultrafast dynamics is represented by an 
N-temperature-model which is commonly applied for ultrafast 
optical excitations. 
Structural dynamics due to thermal stresses are calculated by 
a linear-chain model of masses and springs. 
The resulting X-ray diffraction response is computed by dynamical 
X-ray theory. 
The udkm1Dsim toolbox is highly modular and allows to introduce 
user-defined results at any step in the simulation procedure.

The udkm1Dsim toolbox was developed in the Ultrafast Dynamics 
in Condensed Matter group of Prof. Matias Bargheer at the 
University of Potsdam, Germany. 
The toolbox is currently maintained by Daniel Schick.

## Documentation
The documentation can be found at [readthedocs.io](http://udkm1Dsim.readthedocs.io).

## Citation

Please cite the following article if you use the udkm1Dsim toolbox for your own publications:

D. Schick, A. Bojahr, M. Herzog, R. Shayduk, C. von Korff Schmising & M. Bargheer,
*udkm1Dsim - A Simulation Toolkit for 1D Ultrafast Dynamics in Condensed Matter*,
[Comput. Phys. Commun. 185, 651 (2014)](http://doi.org/10.1016/j.cpc.2013.10.009) [(preprint)](http://www.udkm.physik.uni-potsdam.de/medien/udkm1Dsim/udkm1DsimManuscriptPrePrint.pdf).

## Installation

You can clone udkm1Dsim from the main git repository:

    git clone https://github.com/dschick/udkm1Dsim.git udkm1Dsim

To work in editable mode (source is only linked 
but not copied to the python site-packages), just do:

    pip install -e ./udkm1Dsim

Or to do a normal install with

    pip install ./udkm1Dsim
