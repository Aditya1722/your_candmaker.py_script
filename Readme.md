`your_candmaker.py` is a module of YOUR software which helps to generate astrophysical single pulse candidates. 


* Step 1 - Takes the cand.csv file as input.    
* Step 2 - fucntion `cand2h5`  initialise all the parameter needed to work with from the data -  
> 1. Checks for kill_mask
> 2. Get chunk of data
> 3. Called to fucntion `cpu_dedisp_dmt(cand, args)` for de-dispersion and dmt(dispersion vs time plot) making  -   
    > use the pulse width to decide time decimation factor ( )   
    > Calls `dmtime()`  fucntion to generate the dmt plot   
    > calls `dedisperse()` for dedispersing the data  
    > Frequency - Time, Dispersion - Tme  reshaping  using decimate and resizing.
