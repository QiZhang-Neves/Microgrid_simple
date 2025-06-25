# Microgrid simple implementation

This system is a Python-based implementation that models and optimizes microgrid operations using IBM CPLEX.

- **Input:** The system takes configuration data and constraints related to microgrid components (generators, loads, storage, etc.).  
- **Optimization:** It formulates the microgrid operation as an optimization problem and solves it with CPLEX to find the best operational schedule.  
- **Output:** The result includes optimized schedules and operation costs, which help in efficient energy management.

   This is a rewrite of the original MATLAB implementation found here, now designed to be more accessible in Python.

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


1. Navigate to the folder containing the `environment.yml` file.  
2. Run the following command to create the environment:
   `conda env create -f environment.yml`

---

## Step 3: Install IBM CPLEX (Personal Version)

1. Visit the IBM CPLEX download page:

   https://www.ibm.com/products/ilog-cplex-optimization-studio

2. Register for a free personal-use license (if you don’t have one).  
3. Download and install CPLEX on your system.  
4. Configure environment variables or paths so your code can access CPLEX correctly.

---

## Additional Notes

- To activate the created environment, use:
-  `conda activate your_env_name`
  
- Replace `your_env_name` with the name specified in `environment.yml`.

---

## Attribution

This work is originally a rewrite in Python of the MATLAB version available at:  
https://github.com/zhanguomin/microgrid_Cplex/blob/master/microgrid_Cplex.m

---

If you run into any issues or need further assistance, please feel free to reach out.


