# A Fast and Robust Fourier Option Pricing Method: Defining a Truncation Range Formula Explicitly for Various Advanced Stock Price Models

Being able to price options and multiple strikes at high speed is known to be a very important facet
of computational finance: 

“...stock price models are typically calibrated to gives prices of liquid call and put options by
minimizing the mean-square-error between model prices and given market prices. During the
optimization routine, model prices of call and put options need to be evaluated very often for
different model parameters.” 

The COS Method is a Fourier option pricing technique that allows for options to be priced extremely
quickly. It is in fact the fastest known Fourier transform technique. It was first documented in Fang
and Osterlee’s paper; “A Novel Pricing Method for European Options Based on Fourier-Cosine Series
Expansions”, Fang’s Phd thesis.

There are some outstanding issues with this method pertaining mainly to divergence in some
advanced stock price models, namely L´evy processes with jumps, and major option
pricing errors in extreme moneyness options. Here I examine these issues and implement
solutions I have found in my research. The aim is to formulate a more robust COS-method for
pricing stock options at a very wide range of strikes across numerous advanced stock price models
whilst attempting to maintain the computational efficiency of the COS method.


___
**Note:**
**In /Research is my research paper and the associated jupyter notebook. I recieved 100% for this piece of work. The below is not graded**

***To Do***
- Robust/Fast COS Fourier Pricing Program ($\texttt{.py}$ module)
- Robust/Fast COS Fourier Model Calibrator
