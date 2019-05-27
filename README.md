# sex_diffs

Work by natalie forde 2018/2019

#Investigating sex-diffferences in structural variability in healthy individuals

Atlases: 
Desikan- Killiany

Dataset:
HCP S1200
PNC
OASIS 3
ADNI (only used briefly)

#Variance ratio (VR) 
Univariate analysis of sex differences in variance between individual ROIs from the DK atlas across multiple datasets

Scripts:
> FreeSurfer.Rmd (HCP)
> FreeSurfer_PNC.Rmd
> FreeSurfer_OASIS.Rmd
> FreeSurfer_ADNI.Rmd (no longer using)

For matched data:
> FS_PNC_matched.Rmd
> FS_HCP_matched.Rmd
> FS_OASIS_matched.Rmd

#Mahalanobis Distance
Multivariate analysis of sex differencecs in variance across sets of ROIs (grouped by metric type)

Scripts:
> mahalanobis.RMD
> mahalanobis_matched.Rmd
> mahalanobis_AgeIN.Rmd

#Cosine-Angle
Multivariate analysis of sex differences in the pattern of how ROIs relate to each other 'structural profiles'

Scripts:
> sphere.Rmd

#PCAs
Principle component analysis of the data

Scripts:
> PCA.Rmd

