The file is getting cumbersome by uploading some previous classes repeatly. 
Tired? Now we are going to wrap those useful classes into a py file and simply import it before it's used.
Next, we follow these steps below to reproduce 
the previous bsm_formula notebook - [ipynb](../src/bsm_formula_v01.ipynb)

- copy/paste  "EuropeanOption" class in the previous 
  [ipynb](../src/european_options_class.ipynb), and save it as 
  [src/european_options_class.py](../src/european_options_class.py).
- Similarly, cutting relevant code to the Gbm class from [ipynb](../src/bsm_formula_v01.ipynb), 
  and do not forget to add "import european_options_class" on top, since we use EuropeanOption class.
  Then save it as [src/sde_class.py](../src/sde_class.py).  
- When we reproduce [ipynb](../src/bsm_formula_v01.ipynb), first delelte all codes included in the above two py files, then 
git clone the entire repo, and change your current directory to the "src" folder, then import py files.
- At last, do not forget all class members to be specified after its class, see [ipynb](../src/bsm_formula_v02.ipynb)
