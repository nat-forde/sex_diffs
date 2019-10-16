# sex_diffs

Work by natalie forde 2018/2019  

## Investigating sex-diffferences in structural variability in healthy individuals

Atlases:  
Desikan- Killiany  

Dataset:  
HCP S1200  
PNC  
OASIS 3  
ADNI (only used briefly)

## Variance ratio (VR) 
Univariate analysis of sex differences in variance between individual ROIs from the DK atlas across multiple datasets  

Scripts:  
* FreeSurfer.Rmd (HCP)  
* FreeSurfer_PNC.Rmd  
* FreeSurfer_OASIS.Rmd  
* FreeSurfer_ADNI.Rmd (no longer using)  
  
For matched data:  
* __FS_PNC_matched.Rmd__  
* __FS_HCP_matched.Rmd__  
* __FS_OASIS_matched.Rmd__  
  
## Mahalanobis Distance  
Multivariate analysis of sex differencecs in variance across sets of ROIs (grouped by metric type)  
  
Scripts:  
* mahalanobis.RMD (orig with age & TBV regressed out)  
* mahalanobis_matched.Rmd  
* mahalanobis_AgeIN.Rmd  (age continuous across sample)  
* mahalanobis_AgeBINNED.Rmd  
* __mahalanobis_AgeBINNED_NoTBVcorrection.Rmd__  
* mahalanobis_cosine_Ttest_AGEout_NoTBVcorr.Rmd (contains both mahalanobis and cosine analysis for data with age regressed out but no TBV correction)  
  
## Cosine-Angle
Multivariate analysis of sex differences in the pattern of how ROIs relate to each other 'structural profiles'  
  
Scripts:  
* sphere.Rmd (orig with age & TBV regressed out)  
* cosine_resampled.Rmd (data matched and resampled, age continuous)
* __Cosine_AgeBINNED_NoTBVcorrection.Rmd__  

## PCAs  
Principle component analysis of the data  

Scripts:  
* PCA.Rmd  


