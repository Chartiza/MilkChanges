# 🐮 MilkDHI
Investigation of milk parameters from the DHI laboratory of AO Agroplem.

## Scripts
🥶 *Freez_exp.ipynb*

The script is designed to check DHI milk sample parameters changing before and after freezing. In wintertime, the samples could arrive in the DHI laboratory frozen. We asked the question if we can analyze these samples after heating or if irreversible changes in parameters have already taken place.

As a result, you have Mean Values.pdf and Distr Values.pdf files with the plots that demonstrate parameters changing and the Freez_CorrMatr.jpg file with correlations between parameters.

![All-en](https://user-images.githubusercontent.com/15068419/176672484-d6faa6e8-8991-49ba-87e7-4cae824f2d22.png)

## 
🧮 *СorrectionСoefficients.ipynb*

Script is designed to Comparison of test results of the same milk samples in two different laboratories. The raw data was taken from the DHI laboratory of AO Agroplem and one other DHI laboratory. The analysis was carried out on a FOSS machine and Bently machine. 

<i>Conclusion: </i><br>
We observe a sufficiently high correlation for parameters such as fat, protein and Lactose. <br>
We observe a low correlation for parameters BGB, acetone, FPD.

Fat, % 

 Slope = 0.839 <br>
 Intersept = 0.5 <br>
 R2 = 0.93 

## 
👀 *Comparison_evaluation&real_data.ipynb*

The script is designed to compare evaluation and real data results.

<i>Conclusion: </i><br>
next year's milk and protein evaluations are higher on average, but the real values are not. Possible reason for poor management?

![Yeld_comp](https://user-images.githubusercontent.com/15068419/179762252-a2993d9b-4403-4f2b-b5d3-1836c9b8376b.jpg)

## 
🌡 *FOSS_temp.ipynb*

The script is designed to evaluate correlation between the real probe temperature measured by the logger and the FOSS temperature evaluation.The main objective is to find correction coefficients that can be entered into the standard data processing protocol fo the instrument.<br>

<i>Conclusion: </i><br>
the difference in temperature depends on the day of the experiment (apparently on the ambient temperature in the laboratory). More research is needed to clarify the coefficients.

![FOSS-temp](https://user-images.githubusercontent.com/15068419/177305805-8a82746c-38e4-485b-8e11-5e431df55f9e.png)

##
🥛 *FattyAcid_ratios.ipynb*

Script is designed to calculate fatty acid group proportion.
The raw data was taken from the DHI laboratory of AO Agroplem. The analysis was carried out on a FOSS machine. <br>
A total of 13,107 animals from the Russian population of black-motley Holstein were analysed.

![LCFA_MCFA_SCFA](https://user-images.githubusercontent.com/15068419/176680463-f3be765b-d20d-457c-9a73-758fbfd792ab.png)

##
🥛 *FattyAcidGroups.ipynb*

Script is designed to calculate relative abundance of main fatty acids groups. <br>
The raw data was taken from the DHI laboratory of AO Agroplem. The analysis was carried out on a FOSS machine. <br>
A total of 13,107 animals from the Russian population of black-motley Holstein were analysed.

![MUFA-rel](https://user-images.githubusercontent.com/15068419/176905563-26649c14-c146-4d65-93cf-c5d07a8b09f4.png)
