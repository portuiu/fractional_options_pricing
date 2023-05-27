# Modelling Options prices considering Mandelbrotian movement of prices

The traditional Geometric Brownian Motion model widely used by financial practitioners assumes that each change in price X(t) is random, independent, and normally distributed. There are moments in which the model contradicts reality and these discrepancies in underlying assumptions give a false sense of option price to the traders and analysts who use the classic Black-Scholes model. It results in the misleading evaluation of risks and wrong trading decisions. This paper provides the methodology to model option price movements based on the latest advances of Mandelbrot’s theory of fractal price movements (Fractional and Multifractional Brownian Motion) and provides a comparison with classic pricing models (classic Black-Scholes, Heston models) on a wide range of historical data.

The full paper is available: https://docs.google.com/document/d/1jW2FdozuQ6ADAAehIhqhEMDflRdcjiS_
The detailed description of solution design: https://docs.google.com/document/d/1Zi4uJsbMI7R-1XaGri4U4WaH_FopINYL

# How-to

## Locally
The project requires Jupyter Notebook to be installed: https://jupyter.org/install

1. clone the repository and locate to the project's directory;
2. download the dataset `spx_data.zip` from GDrive and extract to the directory;
3. execute: `source env/bin/activate`;
4. `pip install -r requirements.txt` to install needed dependencies;
5. launch 'jupyter notebook' and run '.ipynb' file.

## Cloud
The project is also available remotely in Datalore Cloud: https://datalore.jetbrains.com/view/notebook/nThPouKjn8gf0tbaYVsvV2
Press "Edit copy" to create your copy of the project and run cells.

# Contributions
Thanks to my supervisor, prof. Joe W. Byers, and WorldQuant University for the courses throughout Financial Engineering Master's.
