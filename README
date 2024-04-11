**Summary**

Facial expression is one of the most natural ways for human beings to communicate their emotional information in daily life. Although the neural mechanism of facial expression has been extensively studied employing lab-controlled images and a small amount of lab-controlled video stimuli, how the human brain processes naturalistic dynamic facial expressions still needs to be investigated. To our knowledge, this type of data specifically on facial expression videos in real-world environments is currently missing. We describe here the Naturalistic Facial Expressions Dataset (NFED), a large-scale dataset of functional magnetic resonance imaging (fMRI) responses to 1,320 short (3s) naturalistic facial expression video clips. The video clips include three categories: positive, neutral, and negative, along with accompanying metadata. We validate that the dataset has good quality within and across participants and, notably, can capture temporal and spatial stimuli features. NFED offers researchers fMRI data that enables them to investigate the neural mechanisms of understanding the processing of emotional information conveyed by facial expression videos in real-world environments. 

**Data record**
The data were freely available at https://openneuro.org/datasets/ds005047, organized according to the BIDS format. The “sub-<subID>” folders store the raw data of each participant. The pre-processed volume data were saved as the “derivatives/pre-processed_volume_data/sub-<subID>” folders, while the pre-processed surface data were saved in the “derivatives/volumetosurface/sub-<subID>” folders.

*Stimulus*
Distinct folders store the stimuli for distinct fMRI experiments: "stimuli", "stimuli/floc", and "stimuli/prf" (Fig. 2b). The category labels and metadata corresponding to video stimuli are stored in the "stimuli/video-category-labels" and "stimuli/video-metadata" folders, respectively.

*Raw MRI data*
 Each participant's folder is comprised of 11 session folders: “sub-<subID>/ses-anat”, “sub-<subID>/ses-<sesID>”. The “ses-anat” folder comprises one folders, named “anat”. The “ses-<sesID>” folder comprises “fmap”and “func” two folders. A “sub-<subID>_ses-<sesID>_scans.tsv” file stores the scan information for a scan session. The task events were saved as “sub-<subID>/func/sub-<subID>_ses-<sesID>_task-<taskID>_run-<runID>_events.tsv” for each run.

*Freesurfer recon-all*
The results of reconstructing the cortical surface were saved as “recon-all-FreeSurfer/sub-<subID>” folders.

*Pre-processed volume data from pre-processing*
 The pre-processed volume-based fMRI data were saved as “pre-processed_volume_data/sub-<subID>/ses-<sesID>” folder. A“sub-<subID>_ses-<sesID>_task-<taskID>_volume_run-<runID>.nii” file stores  the pre-processed volumes data of a run. A “sub-<subID>_ses-<sesID>_task-<taskID>_volume_mean.nii” file stores the mean of the pre-processed volume data of a session. A “sub-<subID>_ses-<sesID>_task-<taskID>_volume_run-<runID>_timeseries.tsv” file stores the head motion of participants. The confounds parameters of co-registration alignment for a session were stored in a file named as “sub-<subID>_ses-<sesID>_task-<taskID>_alignment/alignment.mat”.

*Preprocessed surface-based data*
The pre-processed surface-based data were stored in a file named “volumetosurface/sub-<subID>/ses-<sesID>/sub-<subID>_ses-<sesID>_task-<taskID>_run-<index>_lh/rh.surfacedata.mat” for each run.

*Brain activation data from surface-based GLM analyses*
  The GLM analysis data from the main experiment for a scan session were stored in a file named “GLM/sub-<subID>/sub-<subID>_ses-<sesID>_task-task-<taskID>.mat” file. A “GLM/sub-<subID>/sub-<subID>_ses-<sesID>_task-<taskID>_mean.mat” file stores the mean of the GLM analysis data for the fLoc experiment.

*The technical validation of the NFED*
The code of technical validation were saved as “derivatives/validation/code” folder. The results of technical validation were saved as “derivatives/validation/results” folder.








