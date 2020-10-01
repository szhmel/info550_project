## INFO 550 HW4 instructions

It is a very basic R program for my project
I used library of 'tidyr','tidyverse' and 'data.table'. The required packages can be installed using R commands.


```{r}
installed_pkgs <- row.names(installed.packages())
pkgs <- c("tidyr", "tidyverse","data.table")
for(p in pkgs){
	if(!(p %in% install_pkgs)){
		install.packages(p)
	}
}

```

My project is about linking some birth records with air pollution quality data. I also calculate their trimester averages and present them in table and plot format.

The birth record is the file 'simulated_final' and 'NH4' is my air pollution data.

