The file is getting cumbersome by uploading some previous classes repeatly. 
Tired? Now we are going to wrap those useful classes into a py file and simply import it before it's used.
Next, we follow these steps below to reproduce 
the previous bsm_formula notebook - [ipynb](../src/bsm_formula_v01.ipynb)

- create "european_options_class.py" by copy/paste of "European_Option" class in the previous 
[ipynb](../src/european_options_class.ipynb)
- Similarly create "sde_class.py" by cutting relevant code to the Gbm class. Do not forget import "European_option". [ipynb](../src/bsm_formula_v01.ipynb)
- Copy [ipynb](../src/bsm_formula_v01.ipynb), then delete all info of above two classes, but import two py files above
- When we reproduce [ipynb](../src/bsm_formula_v01.ipynb), first git clone the entire repo, and change your current directory to the "src" folder.
- Do not forget all class members to be specified after its class, see [ipynb](../src/bsm_formula_v02.ipynb)
