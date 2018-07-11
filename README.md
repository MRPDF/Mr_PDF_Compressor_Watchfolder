# Mr_PDF_Compressor_Watchfolder
This is extending ActivePDF_Compressor so that it now has a watchfolder system. The application creates a watchfolder on their Windows Desktop so that they can drop their pdf files into the input folder for compressing. If the compression fails it generates a logfile with the reason for failure. There is also a JSON file used for configuring the compressor. 


In order for the Compressor component to work be sure to go to https://www.activepdf.com/products/compressor and download the Compressor API and add the DLL (C:\Program Files\activePDF\Compressor\bin\APCompressor.Net45.dll) file to this Visual Studios project. 
