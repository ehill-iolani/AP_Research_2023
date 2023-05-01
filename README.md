# AP_Research_2023
A collection of nonsense made by EH for AP research

# Set up instructions
Follow the steps below to set up the env you'll be working on

Select "make new codespace from master" then enter the following command into the terminal:
```
docker pull rocker/rstudio
```

Once the download has completed, run the following command:
```
docker run --rm -ti --volume=/workspaces/AP_Research_2023:/home/Documents -p 8787:8787 rocker/rstudio
```

Wait for the virtual machine to spin up then follow the link under the "ports" section of the terminal tabs

Follow the ports link then enter the username and password:

username: rstudio

password: randomly generated, look at the terminal

Once you have logged in, click the three dots by the file path menu and enter:
```
/home/Documents
```

Then click the gear icon and select "Set as working directory"

# Actual content we'll be covering

We'll first mess with "covidfun.R". The documentation can be found here: 
https://github.com/hilletc7/low-budget-covid19-tracker

Next we'll mess with "plotting_stub.R" The documentation for this one is built into the script

Finally, we'll mess with "sassysqrt.R". The documentation can be found here: 
https://github.com/hilletc7/sassy-square-root-function
