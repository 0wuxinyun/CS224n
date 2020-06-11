# Anaconda Setup 

## Use conda conmand in terminal :

> Problem faced: -bash: conda: command not found 

#### Solution:
	$ vim ~/.bash_profile
In the ~/.bash_profile key `i` : insert model and add this one line below:

	export PATH="/anaconda3/bin:$PATH"

key `esc` to exit and key `:wq` to save and exit the file 

Activate the environment :

	source ~/.bash_profile
	
> Problem faced:  
> CommandNotFoundError: Your shell has not been properly configured to use 'conda activate'.

#### Solution :

	conda init bash
