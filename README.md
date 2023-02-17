# Data-fusion-for-estimating-ambient-air-pollution-with-spatial-disalignment

Hello World! :wave:  

This is the README of the  project of Bayesian Statistics Course (Academic Year 2022/2023).

## How to navigate this sea of documents :ocean:

  The project was carried out using two programming languages: R and (little C++).
  This is the content of the documents we have attached:

  1) _**Simulated_Data.R**_           : here you can find the R code of our complete model. More accurately we create Simulated Data. 
                                    From the derived Full Conditionals we run the Gibbs Sampler and finally we make prediction using 
				    kriging method for unkonwn locations.
            
  2) _**Real_data Natural Sea.R**_      : we follow the same modus operandi of Simulated_Data, but in this case using Real Data. 

  3) _**Real_Data Flat Sea.R**_         : this code is speculate to the Real_data Natural Sea, but we change the covariate (population density) 
                                    taking into account the "sea problem".
		    
  4) _**Real_Data Intercept Model.R**_  : here we run our code with simplified model (y = b0 +b0(s)) to overcome the absence of CMAQ data.
  
  5) _**Rcpp_Kernel.Cpp**_              : this function uses Rcpp and RcppArmadillo to compute the covariance matrix. 
                                    It optimizes the slow R for-loops and it compute efficiently the squared exponential covariance 
                                    function of every entry of the input matrices. 
				 
  6) _**Report.pdf**_ : this is the report of the project.
  
  7) _**Presentation.pdf**_ : here it is the presentation of the project.
  
  
  Also, last but not least, the datasets to run the codes placed in this folder: 

  6) _**DATASETS.zip**_


Bon voyage! :boat:

## Team members
  * [G. Barbato]()
  * [M. Cosi](https://github.com/michelecosi)
  * [M. Del Basso](https://github.com/martidb2000)
  * [C. Esposito]()
  * [A. Frabetti](https://github.com/ale1998bo)        
  * [M. Rizzo]()    
