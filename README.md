  Bifurcation-Analysis
 =======================
This code is written in Maple and help us to analyze the changing behavior of system as one, two parameters are being varied.
Here, all setting are defined for Yersinia enterocolitica co-infection in specific-pathogen-free (SPF), germ-free (GF), and MyD88-deficient (MyD88) mut mice.


----
*Author*: [Reihaneh Mostolizadeh](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/systems-biology/team/dr-reihaneh-mostolizadeh/)


*Citation*: Please cite us [https://www.mdpi.com/2079-7737/9/12/431](https://www.mdpi.com/2079-7737/9/12/431)

► Getting started with NCMW
----------------------------

All information regarding the usage of codes can be found in main.mws.
Please see the main.mws at the firts step.

Overview
--------

 ** main.mws**: 
- Red parts are highlighted in this workbook which indicates the main code. All names and variables used in the workbook are explained based on parameters and variables defined in the dynamic model.
- Initial conditions are defined based on three different types of mice used in the experimental (SPF, GF, MyD).
- Target parameters for the bifurcation analysis are chosen.
- Plots are conceptualized based on the purpose and the analysis. 

 ** SPF.mw**: 
- This workbook specifies all settings for Yersinia enterocolitica co-infection in specific-pathogen-free (SPF) mice (Figure 6 (a,d), Figure 7 (a,d), Figure 8 (a,d), Figure 9 (a,d) of publication).

 ** GF.mw**: 
- This workbook specifies all settings for Yersinia enterocolitica co-infection in germ-free (GF) mice (Figure 6 (b,e), Figure 7 (b,e), Figure 8 (b,e), Figure 9 (b,e) of publication).

 ** MyD.mw**: 
- This workbook specifies all settings for Yersinia enterocolitica co-infection in MyD88-deficient (MyD88) mut mice (Figure 6 (c,f), Figure 7 (c,f), Figure 8 (c,f), Figure 9 (c,f) of publication).

 ** CenterManifold**:
 - This workbook shows the approaches for calculation of center manifold. However, the center manifold calculation can be more precise if we compute the additional terms in the reduced system through Normal forms. Due to the complexity of Normal forms' calculation in a large system with many parameters, the Normal form calculation approach was not made entirely. This does not cause any problem in the system analysis since the aim for calculation of center manifold was only identifying sign and direction of simple zero in free-disease equilibrium, which was achieved. Therefore the sign of simple zero proved that free-disease equilibrium is stable as long as (R[0])^wt < 1 and (R[0])^mut < 1.

** Figure4, Figure 5, Figure 10**:
- These workbooksstand for the associated figures of publication.


☮ Licensing and distribution
----------------------------

The University of Tübingen, Germany

Codes are freely avilable. You can apply them into your dynamic model and/or modify them based on your purpose. Please cite us [https://www.mdpi.com/2079-7737/9/12/431](https://www.mdpi.com/2079-7737/9/12/431).
