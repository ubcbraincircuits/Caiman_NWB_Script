# Caiman_NWB_Script
The intention of this script is to run caiman analysis on a .tif file and then proceed to extract and analyze dF/F data. It is best to execute the scripts in the following order on Jupyter notebook:

1) The first script to run is the demo_pipeline_NWB_DMBCH.ipynb which runs caiman analysis on a .tif file and saves processed data as an NWB file. <br>
2) The second script to run is the NWB_dF_F.ipynb which allows you to write the dF/F values from the caiman analysis into the NWB file. <br>
3) The last script to run is Combining_dFF_Values.ipynb enables to pool the dF/F values from different movies and view them on a single graph. <br>

Please note that these scripts are slightly different from the ones provided when Caiman is installed; they have been adjusted to better suit the needs of the centre.

Additional note: I have provided the cropped .tif files I have used in order to run Caiman analysis: <br>
m3_00002_cropped1.tif <br>
m3_00002_cropped2.tif <br>
m3_00002_cropped3.tif <br>

I have also provided the NWB created upon running caiman for each corresponding .tif file.
