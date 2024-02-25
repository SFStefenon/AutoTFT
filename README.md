# Hypertuned Temporal Fusion Transformer for Multi-Horizon Time Series Forecasting

This repository presents an application of the automatic hyperparameters tuning temporal fusion transformer [(AutoTFT)](https://github.com/SFStefenon/AutoTFT/blob/main/TFT.ipynb) model for time series forecasting of dam level in a hydroelectric power plant.
The methodology of this application is according to:

![image](https://github.com/SFStefenon/AutoTFT/assets/88292916/3851a691-8810-4fa7-8a16-3bb504b75619)

The considered [data](https://github.com/SFStefenon/AutoTFT/blob/main/data.csv) is based on measurements from the automatic hydraulic control of a hydraulic power plant during a flood. In 20 days and 1 h, the level of the dam increased from 20.46% to 86.27%. 
The recorded data is from a hydraulic power plant located in Pelotas River, Santa Catarina State, Brazil. The measurements were recorded in July 2020, considering a time interval of 1h, corresponding to 481 records. 

In this application, an evaluation of multi-horizon time series forecasting is performed wherein a median term is compared to the short-term forecasting given *P*-steps ahead: 

![image](https://github.com/SFStefenon/AutoTFT/assets/88292916/a7692d89-ab25-47b9-9cb0-970acc99e300)

**Please go ahead and try it on [Google Colab](https://colab.research.google.com/github/SFStefenon/AutoTFT/blob/main/TFT.ipynb)!**

---

Additional information can be found at the **[Original Paper](https://doi.org/10.1016/j.ijepes.2024.109876)**.

Stefenon, S. F., Seman, L. O., Silva, L. S. A., Mariani, V. C., Coelho, L. S. Hypertuned temporal fusion transformer for multi-horizon time series forecasting of dam level in hydroelectric power plants, International Journal of Electrical Power & Energy Systems, vol. 157, p. 109876, 2024.

BibTeX:
`@article{STEFENON2024109876, author = {Stefano Frizzo Stefenon and Laio Oriel Seman and Luiza Scapinello Aquino da Silva and Viviana Cocco Mariani and Leandro dos Santos Coelho}, title = {Hypertuned temporal fusion transformer for multi-horizon time series forecasting of dam level in hydroelectric power plants}, journal = {International Journal of Electrical Power \& Energy Systems}, volume = {157}, pages = {109876}, year = {2024}, doi = {10.1016/j.ijepes.2024.109876}}`

---

Thank you.

Dr. **Stefano Frizzo Stefenon**

Trento, Italy, August 10, 2023.
