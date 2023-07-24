# breastcancerseg
Automatic cancer segmentation in breast DCE-MRI.

## Data preparation 
Anonymized dicom files were converted to compressed nifti format using [dcm2nii](https://github.com/rordenlab/dcm2niix).
- T1_pre.nii.gz
- T1_post.nii.gz
- T1_post_delayed.nii.gz
  
The side containing cancer and the side without cancer were separately stored.
- cancer/T1_pre.nii.gz, cancer/T1_post.nii.gz, cancer/T1_post_delayed.nii.gz
- contra/T1_pre.nii.gz, contra/T1_post.nii.gz, contra/T1_post_delayed.nii.gz

