# Rare_Gems_Demo

<img src="https://github.com/lincc-frameworks/Rare_Gems_Demo/assets/12860669/6ddcd206-d962-4d9f-8937-b6a6dbd31adc" alt="Rare Gems Poster" width="300">



Installation 

```
>> conda create --name lincc python=3.10
>> conda activate lincc
>> pip install lsdb
>> pip install lf-tape
```

Ideas what to show:

- Notebook 1
  - Installing lsdb (conda or pip) and tape (pip) 
  - Loading small part of ZTF and GAIA DATA, with only ra and dec
  - Do crossmatch
  - Saving the result
    
- Notebook 2
  - Loading small part of ZTF and GAIA DATA, with all columns
  - Do crossmatch
  - Compare times from previous notebooks
  - Load the result from notebook 1
  - Compare the results
  - Explain Dask and lazy loading
  - Show that you loaded whole partitions
    
 - Notebook 3
   - Discuss partitioning of the sky
   - Show how to get exact part of the sky
   - Do a query?   
   - Load a catalog from Vizir
   - crossmatch that one too?
    
- Notebook 4
  - (Optional) Connect to Dask dashboard?

- Notebook 5
  -(Optional) showcase margins

- Notebook 6 (Andy T.)
  - Loading Tape
  - Running a function on the lightcurves
  - Find the most interesting?
  - Plot the results
