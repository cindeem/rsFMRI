
Processing Outline
==================

Anatomical
----------


 #. get items form freesurfer
    #. brainmask
    #. aparc_aseg (Desikan Atlas)
    #. aparc_2009 (Destrieux Atlas)

 #. Generate white matter mask
    #. erode?
 #. generate CSf mask 
    #. erode
 #. mask brainmask with aparc to get improved skull strip?
 #. generate GM mask
 #. put thickness vals into volume space (subcortical)
    #. vbm approach??
 

Functional
----------

 #. slicetiming
 #. realign (unwarping?)
    #. movement parameters
 #. detrending?
 #. qa (dealing with bad frames)
 #. Coreg anat -> rsfmri
 #. bandpass timeseries and regressors
 #. define regressors (derivatives?)
 #. pull ROI regresssors( WhiteMatter, ventricles)
 #. design matrix
 #. regress out regressors -> residuals
 #. get roi vals
    #. desikan + subcortical
    #. destrieux + subcortical
 #. nittime  partial correlation, correlation, coherence




