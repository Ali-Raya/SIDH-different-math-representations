# SIDH-different-mathematical-representations
# Analyzing the Performance of SIDH Protocol using Different Implementations of the Elliptic Curve

This repository ilustrates the impact of using different mathematical representations on the running time of SIDH protocol 
## Description of the implementation:
- FP2.ipynp: contains the arithmetic of $F_P$ and $F_P^2$ is implemented using gmpy2 module.
- 1.EW-short_Weierestress_Final_Real_world_example-implemnted-DEMO.ipynb contains the implemetation of SIDH where the arithmetic of  affine short Weierestrass curve is used.
- 2.EM_Affine_Coordinates_Real_world_examples_DEMO.ipynb contains the implemetation of SIDH where the arithmetic of affine Montgomery curve is used.
- 3.EM_Projected_coordinates_Real_world_examples_without_strategies.ipynb contains the implementation of projecetd curve is used.
- 4.EM_Projected_coordinates_optimized_Final_Real_world_with_strategies .ipynb contains the implementation of the projecetd Montgomery curve where the optimal strategies are introduced.
- Drawing Figures.ipynb contains the command that draws the final figures and compare the measurments.

### Running the code

1. First, you have to install Sagemath if you haven't already, refer to: https://doc.sagemath.org/html/en/installation/index.html
2. install  packages used in the code:
```bash
        pip install hwcounter
	pip install import-ipynb
	pip install numpy
	pip install ipython
	pip install pandas
	pip install gmpy2
3. Run .ipynbfiles in order (i.e, 1,2,3,4).

The measurements after running each file will be saved seperately for the pk and shared key in cpu_measurement.txt and time_measurement.txt and combined in the files cpu_measurement_combined.txt and time_measurement_combined.txt
4. Run the file Drawing Figures.ipynb and you can find the detailed measurments for both of Alice and Bob.
        
