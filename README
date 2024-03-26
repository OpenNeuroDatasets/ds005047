**Summary**

Facial expression is one of the most natural ways for human beings to communicate their emotional information in daily life.While the neural mechanism of facial expression has been widely studied using lab-controlled images and small amount of videos stimuli,how the human brain processes naturalistic dynamic facial expression still needs to be explored. However,this type of data is currently missing.Here,we describe the Naturalistic Facial Expressions Dataset (NFED),a large-scale dataset of whole-brain functional magnetic resonance imaging (fMRI) responses to 1,320 short (3s) facial expression video clips.The video clips encompass three expressive categories:positive,neutral,and negative.We validated that the dataset has good quality within and across participants and,notably,can encode temporal and spatial stimuli features in the brain.NFED provides researchers with fMRI data that can be used not only to explore the neural mechanisms underlying the processing of emotional information conveyed by naturalistic dynamic facial expression stimuli,but also to more effectively characterize the relationship between perceived stimuli and brain responses through neural encoding and neural decoding.

**Data record**

The data were organized according to the Brain-Imaging-Data-Structure (BIDS) Specification version 1.0.2 and can be accessed from the OpenNeuro public repository (accession number: XXX). In short, raw data of each subject were stored in “sub-<ID>” directories; The pre-processed volume data and the  surface-based data can be found in “derivatives/pre-processing” and “derivatives/volumetosurface” directories, respectively.

*Stimulus*
The stimulus for different fMRI experiments are stored in different folders: “stimuli”, “stimuli/floc” ,and “stimuli/prf”.The category labels and metadata corresponding to video stimuli are stored in “stimuli/video-category-labels” and “stimuli/video-metadata”directories, respectively.

*Raw MRI data*
Each participant's folder is comprised of 11 session folders: “sub-<subID>/ses-anat” ,“sub-<subID>/ses-<sesID>”.The “ses-anat” folder comprises one folders, named “anat”.The “ses-<sesID>” folder comprises two folders,named“func” or “fmap”.A “sub-<subID>/sub-<subID>_ses-<sesID>_scans.tsv” file stores the scan information for a scan session.The task events were saved as“sub-<subID>/func/sub-<subID>_ses-<sesID>_task-<taskID>_run-<runID>_events.tsv”for each run.

*Freesurfer recon-all*
The results of reconstructing the Cortical Surface were saved as “derivatives/recon-all-FreeSurfer/sub-<subID>” folders

*Pre-processed volume data from pre-processing*
The pre-processed volume-based fMRI data were saved as“pre-processed_volume_data/sub-<subID>/ses-<sesID>/sub-<subID>_ses-<sesID>_task-<taskID>_volume_run-<runID>.nii”.A“sub-<subID>_ses-<sesID>_task-<taskID>_volume_run-<runID>_timeseries.tsv” folder stores the head  motion of participants.A “sub-<subID>_ses-<sesID>_task-<taskID>_volume_mean.nii” file stores  the mean of the pre-processed volumes data of a scan session. The confounds parameters of co-registration alignment for a session were saved as “sub-<subID>_ses-<sesID>_task-<taskID>_alignment/alignment.mat” file.

*Preprocessed surface-based data*
The pre-processed surface-based data were saved as “derivatives/volumetosurface/sub-<subID>/ses-<sesID>/sub-<subID>_ses-<sesID>_task-<taskID>_run-<index>_lh/rh.surfacedata.mat” for each run.

*Brain activation data from surface-based GLM analyses*
 The GLM analysis data of main experiment for a scan session were saved as “derivatives/GLM/sub-<subID>/sub-<subID>_ses-<sesID>_task-task-<taskID>.mat”files.A“derivatives/GLM/sub-<subID>/sub-<subID>_ses-<sesID>_task-<taskID>_mean.mat” file  stores the mean of the GLM analysis data for Functional localizer experiment.

*The technical validation of the NFED*
The results of the technical validation were saved as “derivatives/validation/results” for each participant.The code of the technical validation were saved as “derivatives/validation/code”.
