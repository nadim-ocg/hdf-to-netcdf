# hdf-to-netcdf
This notebook contains python code to convert HDF4 dataset into an xarray or netCDF file, WHICH DOES NOT PROVIDE LATITUDE AND LONGITUDE VALUE DIRECTLY. An HDF4 file is basically hard to read and manipulate using python, it does not have that much flexibility as xarray. 
There's an web tutorial about how to read MODIS HDF4 file using GDAL, rioxarray and xarray, but that will not work if you do not compile GDAL with HDF4 driver enabled. And that is frustrating to do.
So, I used pyhdf to access the data in an HDF4 file.
Installation of PyHDF also require a normal installation of HDF4 on your system. You can do it easily by following the web instructions. Then setup the environmental variables and you can easily install pyhdf using "pip install pyhdf".
If you face problems regarding this, then feel free to ask me at nadimrahman087@gmail.com.

Best of Luck!.
