Node: highpass (fsl)
====================


 Hierarchy : level1.highpass
 Exec ID : highpass.b3


Original Inputs
---------------


* args : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* in_file : ['/home/runner/work/example-notebooks/example-notebooks/books/functional_imaging/output_level1/level1/_subject_id_04/intnorm/mapflow/_intnorm0/sub-04_task-flanker_run-1_bold_dtype_mcf_thresh_smooth_maths_intnorm.nii.gz', '/home/runner/work/example-notebooks/example-notebooks/books/functional_imaging/output_level1/level1/_subject_id_04/intnorm/mapflow/_intnorm1/sub-04_task-flanker_run-2_bold_dtype_mcf_thresh_smooth_maths_intnorm.nii.gz']
* in_file2 : <undefined>
* mask_file : <undefined>
* op_string : ['-bptf 25 -1 -add /home/runner/work/example-notebooks/example-notebooks/books/functional_imaging/output_level1/level1/_subject_id_04/meanfunc3/mapflow/_meanfunc30/sub-04_task-flanker_run-1_bold_dtype_mcf_thresh_smooth_maths_intnorm_maths.nii.gz', '-bptf 25 -1 -add /home/runner/work/example-notebooks/example-notebooks/books/functional_imaging/output_level1/level1/_subject_id_04/meanfunc3/mapflow/_meanfunc31/sub-04_task-flanker_run-2_bold_dtype_mcf_thresh_smooth_maths_intnorm_maths.nii.gz']
* out_data_type : <undefined>
* out_file : <undefined>
* output_type : NIFTI_GZ
* suffix : _tempfilt

