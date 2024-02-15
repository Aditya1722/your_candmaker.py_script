`your_candmaker.py` is a module of YOUR software which helps to generate astrophysical single pulse candidates. 


* Step 1 - Takes the cand.csv file as input.    
* Step 2 - fucntion `cand2h5`  initialise all the parameter needed to work with from the data -  
> 1. Checks for kill_mask
> 2. get chunk of data
> 3. Called to fucntion `cpu_dedisp_dmt(cand, args)` for de-dispersion -   
    > use the pulse width to decide time decimation factor 
    >
