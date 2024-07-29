This is the GitHub repository for the project **Self-supervised Deep Normative Learning for the Detection of Subcortical Anomalies in Ataxia-Telangiectasia**.

All analyses are included in the Jupyter Notebook _main.ipynb_, uploaded here.

## Abstract
### Purpose
To develop a normative self-supervised deep autoencoder using brain diffusion and perfusion features from a healthy population and apply it in patients with Ataxia-Telangiectasia (A-T) to uncover feature abnormalities based on their reconstruction errors (RE).

### Materials and Methods
Mean values of apparent diffusion coefficient and cerebral blood flow perfusion maps were extracted from seven regions of interest: caudate, hippocampus, pallidum, putamen, thalamus, cerebellar gray matter (CGM), and cerebellar white matter (CWM). A normative deep autoencoder that reconstructs these features was trained on healthy subjects, and the reconstruction errors for both healthy and  A-T participants were computed. Shapley Additive Explanation values were used to identify influential prediction features. Lastly, the associations between REs and clinical scores in A-T patients were evaluated.

### Results
Features were correctly reconstructed in controls but not participants with A-T, who showed significantly higher RE. Values of hippocampus, caudate and putamen diffusion, and caudate and putamen perfusion were overestimated in participants with A-T. Cerebellar diffusion and pallidum perfusion were underestimated. Explainability showed that caudate, putamen, and hippocampus perfusion had the greatest influence in reconstruction of perfusion values. The greatest impact for diffusion was caused by cerebellar diffusion and caudate perfusion. 

### Conclusion
Our findings suggest that pallidum, caudate, and CGM could be targets for novel treatment approaches for A-T. Moreover, our findings enable the analysis of subtle circulatory anomalies at an individual level, allowing a tailored approach.

### Keywords
Cerebellum, MRI, movement disorders, autoencoder, deep learning


