# ProyIII-Group07-3CD-Analysis of the Response to Pembrolizumab Treatment in Patients with NSCLC- Lung Cancer.
This repository contains all the data and scripts needed to perform the analysis described. Explore and use these resources to delve deeper into our findings and methodologies.
Este proyecto se centra en el análisis avanzado de datos de pacientes con cáncer de pulmón de células no pequeñas (NSCLC) tratados con Pembrolizumab en etapas avanzadas. Utilizando diversas técnicas estadísticas y de aprendizaje automático, el objetivo es predecir las variables más influyentes en la evaluación inicial de la enfermedad y la respuesta al tratamiento, así como realizar un análisis de supervivencia. Este estudio no solo busca mejorar la personalización y efectividad de los tratamientos para el cáncer de pulmón, sino también contribuir a los Objetivos de Desarrollo Sostenible relacionados con la salud y bienestar, la innovación médica y las asociaciones para alcanzar las metas.

## Repository Structure
- `Gantt_diagram.xlsx`: Gantt chart of the project.
- `Base_Pembro_1L_february_24__v2.xlsx`: Datasets used in the first data processing performed in `Treatment.Rmd`.
- `df_survival.csv`: dataset used to do the survival analysis, `survival_model.Rmd`. 
- `df_definitive.xlsx`: dataset to perform `PCA.Rmd` and `Linear Regression Model using PCA.Rmd`. 
- `df_definitive-2.xlsx`: dataset used to perform `RF_First-Eval.Rmd` and `RF_best_response.Rmd`. 
- `Linear Regression Model using PCA.Rmd`: Script for linear regression analysis.
- `ODS.pptx`: PowerPoint presentation with the ODS supported by the project.
- `PLS_M2_FINAL.Rmd`: Partial Least Squares Model.
- `RF_First-Eval.Rmd`: Random Forest model for the prediction of the first evaluation.
- `RF_best_response.Rmd`: Random Forest model for the prediction of the best response.
- `Treatment.Rmd`: R script for the initial treatment of the data.
- `XGBoost.Rmd`: XGBoost model implementation.
- `survival_model.Rmd`: Patient survival analysis.
- `PROYIII-GROUP07.pdf`: Document with the complete project report.

## Documentation
 [1] S. v. Buuren and K. Groothuis-Oudshoorn. “mice: Multivariate Imputation by Chained
 Equations inR”. J. Statistical Softw., vol. 45, n.º 3. 2011. Accessed May 21, 2024. [Online].
 Available: https://doi.org/10.18637/jss.v045.i03
 
 [2] J. A. Rodrigo. “Análisis de Componentes Principales (Principal Component Analysis,
 PCA) y t-SNE”. Cienciadedatos.net. 2017 June. Accessed May 21, 2024. [Online]. Available:
 https://cienciadedatos.net/documentos/35_principal_component_analysis 

[3] K. H. Liland, B. Mevik, R. Wehrens and P. Hiemstra. “Partial Least Squares and
 Principal Component Regression”. 2017 November. Accessed May 21, 2024. [Online]. Available: https://cran.r-project.org/web/packages/pls/pls.pdf

 [4] S. Kucheryavskiy. “Partial Least Squares Discriminant Analysis”. (s.f.). Accessed May 21, 2024. [Online]. Available: https://search.r-project.org/CRAN/refmans/mdatools/html/plsda.html

[5] A. Vehtari, A. Gelman and J. Gabry. “Practical Bayesian model evaluation using leave-one-out cross-validation and WAIC”. Statist. Comput., vol. 27, n.º 5, pp. 1413–1432. 2016 August. Accessed May 21, 2024. [Online]. Available: https://doi.org/10.1007/s11222-016-9696-4

[6] B. Greenwell and B. Boehmke. “Variable Importance Plots—An Introduction to the vip Package”, R J., vol. 12, n.º 1, p. 343. 2020. Accessed May 21, 2024. [Online]. Available: https://doi.org/10.32614/rj-2020-013

[7] B. Hamner, M. Frasco and E. LeDell. “Evaluation Metrics for Machine Learning”. 2022 October. Accessed May 21, 2024. [Online]. Available: https://cran.r-project.org/web/packages/Metrics/Metrics.pdf

[8] L. Breiman. “Random Forest”. Mach. Learn., vol. 45, n.º 1, pp. 5–32. 2001. Accessed May 21, 2024. [Online]. Available: https://doi.org/10.1023/a:1010933404324

[9] M. N. Wright and A. Ziegler. “ranger: A Fast Implementation of Random Forests for High Dimensional Data in C++ and R”.  J. Stat. Soft., vol. 77, no. 1, pp. 1–17. 2017 March. Accessed May 21, 2024. [Online]. Available: https://doi.org/10.18637/jss.v077.i01

[10] T. Chen et al. “Extreme Gradient Boosting”. 2024 January. Accessed May 21, 2024. [Online]. Available: https://cran.r-project.org/web/packages/xgboost/xgboost.pdf

[11] T. G. Clark, M. J. Bradburn, S. B. Love y D. G. Altman, “Survival Analysis Part I: Basic concepts and first analyses”. Brit. J. Cancer, vol. 89, n.º 2, pp. 232–238. 2003 July. Accessed May 21, 2024. [Online]. Available: https://doi.org/10.1038/sj.bjc.6601118

[12] A. Allignol and A.Latouche. “CRAN Task View: Survival Analysis”. 2023 September. Accessed May 21, 2024. [Online]. Available: https://CRAN.R-project.org/view=Survival.


