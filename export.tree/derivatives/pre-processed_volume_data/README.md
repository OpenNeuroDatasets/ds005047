##Volume data from pre-processing

The pre-processed volume-based fMRI data were in the folder named “pre-processed_volume_data/sub-<subID>/ses-<sesID>” (Fig. 2d). A “sub-<subID>_ses-<sesID>_task-<taskID>_space-individual_desc-volume_run-<runID>.nii” file stores the pre-processed volumes data of a run. A “sub-<subID>_ses-<sesID>_task-<taskID>_space-individual_desc-volume_mean.nii” file stores the mean of the pre-processed volume data of a session. A “sub-<subID>_ses-<sesID>_task-<taskID>_space-individual_desc-volume_run-<runID>_timeseries.tsv” file stores the head motion of participants.The  explanation of head motion parameters were in the folder named “sub-<subID>_ses-<sesID>_task-<taskID>_space-individual_desc-volume_run-<runID>_timeseries.json”. The parameters of co-registration alignment for a session were stored in the folder named “sub-<subID>_ses-<sesID>_task-<taskID>_alignment”.

## matchvol.png and vol.png

"matchvol.png" is the structural image, while "vol.png" is the functional image.  "matchvol.png" and "vol.png" allow for manual inspection of the registration status of a session.