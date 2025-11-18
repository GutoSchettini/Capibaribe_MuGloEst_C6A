# Capibaribe_MuGloEst_C6A

Data analysis of Capibaribe estuary field campaign - Valle-Levinson &amp; Schettini paper

We include here the pre-processed data (pickle files) and the main Jupyter notebooks 


1) Muglo_C6A_adcps_part1.ipynb : organize the order of the moorings - Pickle 'ADCP_in_order.pkl'.
   Muglo_C6A_adcps_part1.html -> if you run the notebbok, there will be an error when try to load
   the raw data, and you don´t see the rest (the plots). Open the HTML to visualize it

3) Muglo_C6A_adcps_part2.ipynb : pre-process the ADCP data, surface cutoff, sigma levels, rotation  

4) Muglo_C6A_CTS.ipynb : order and pre-process the CTs data  

5) Muglo_C6A_merge_adcp_ct : synchronize the ADCP and CT data - Pickle 'Muglo_6ADCP_CT_dic.pkl'  

6) Muglo_C6A_filter_design : design and test filter to be used (cutoff 2 hours)  

7) Muglo_C6A_Figure_02 : do the Figure 2, presentation of the data (currents and salinity)  

8) Muglo_C6A_Figure_03 : do the Figure 3, phase diagrams (water leve, currents (surf/bott), salinity (surf/bott)  

9) Muglo_C6A_Figure_04&05 : do the Figures 4 and 5, Calculation Eq. 4, phase diagrams drho/dt... surface (fig 4) and botton (fig 5)  

10) Muglo_C6A_Figure_06 : do the Figure 6, Calculations Eq. 5, phase diagrams  

11) Muglo_C6A_Figure_07 : do the Figure 7, Richardson Number  

12) Muglo_C6A_Figure_08&09 : do the Figures 8 and 9, time-averaged density and residual currents  






