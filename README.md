# Weather Research and Forecasting (WRF) model
WRF is a state-of-the-art atmospheric modeling system designed for both meteorological research and numerical weather prediction. It offers a host of options for atmospheric processes and can run on a variety of computing platforms. WRF excels in a broad range of applications across scales ranging from tens of meters to thousands of kilometers. For more information, check out: (https://www2.mmm.ucar.edu/wrf/users/)
# Namelist.wps
The namelist.wps is used for running the WRF Preprocessing system (which includes geogrid.exe, ungrib.exe, and metgrid.exe). Multiple columns are used for multiple domains; however max_domains determines how many columns will be used. For example, if you use 3 columns, but only set max_dom = 2, the last column will be ignored.
# Namelist.input
The namelist.input is used for running the WRF model (which includes real.exe, wrf.exe, tc.exe, and ndown.exe). Multiple columns are used for multiple domains; however max_dom determines how many columns will be used. For example, if you use 3 columns, but only set max_dom = 2, the last column will be ignored.
NOTE: Not all parameters have mulitple columns. 
