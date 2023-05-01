# AP_Research_2023
A collection of nonsense made by EH for AP research

Follow the steps below to set up the env you'll be working on

Select "make new codespace from master" then enter the following command into the terminal:
```
docker pull rocker/rstudio
```

Once the download has completed, run the following command:
```
run: docker run --rm -ti --volume=/ -p 8787:8787 rocker/rstudio
```

Follow the ports link then enter the username and password:
username: rstudio
password: randomly generate, look at the terminal

We'll first mess with "covidfun.R". The documentation can be found here: 
https://github.com/hilletc7/low-budget-covid19-tracker

Next we'll mess with "plotting_stub.R" The documentation for this one is built into the script

Finally, we'll mess with "sassysqrt.R". The documentation can be found here: 
https://github.com/hilletc7/sassy-square-root-function
