# Project Setup Instructions

## Prerequisites

- Anaconda (for Python environment management)  
- IBM CPLEX Optimizer (Personal version)

---

## Step 1: Install Anaconda

If you don’t have Python installed, download and install Anaconda from:

https://www.anaconda.com/products/distribution

---

## Step 2: Create the Conda Environment

1. Open a terminal (or Anaconda Prompt on Windows).  
2. Navigate to the folder containing the `environment.yml` file.  
3. Run the following command to create the environment: 'conda env create -f environment.yml'

---

## Step 3: Install IBM CPLEX (Personal Version)

1. Visit the IBM CPLEX download page:

   https://www.ibm.com/products/ilog-cplex-optimization-studio

2. Register for a free personal-use license (if you don’t have one).  
3. Download and install CPLEX on your system.  
4. Configure environment variables or paths so your code can access CPLEX correctly.

---

## Additional Notes

- To activate the created environment, use: 'conda activate your_env_name'
- 
- Replace `your_env_name` with the name specified in `environment.yml`.

---

## Attribution

This work is originally a rewrite in Python of the MATLAB version available at:  
https://github.com/zhanguomin/microgrid_Cplex/blob/master/microgrid_Cplex.m

---

If you run into any issues or need further assistance, please feel free to reach out.


