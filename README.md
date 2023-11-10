# PulmonaryVesselSeg_SurgicalPlanning

Lung cancer is one of the leading causes of cancer-related morbidity and mortality worldwide, with an estimated 1.8 million deaths annually.
Lung surgery especially segmentectomy has been the main treatment of lung cancer patients, in which precise cut of the affected lung part without affecting pulmonary arteries and veins is the key consideration.
Otherwise, bleeding and increased surgical resection may happen during lung surgery if the anatomic structure of the patient is not well awared.
Recently, 3D visualization including visual reality (VR) and 3D printing has been used for lung cancer surgery planning in which surgeons can obtain a vivid understanding of the anatomic structures.
However, in current clinical practice, pulmonary arteries and veins are manually segmented, which is time-consuming, costly, and lacks reproducibility.

Our dataset comprises 95 3D CT scans obtained from Siemens’ SOMATOM Definition Flash machine. The patients’ age ranges from 29 to 82 years, with an average of 58.4 years. The images have a size of 512 × 512×(280−370) voxels, with a typical voxel size of 0.25×0.25×0.5mm3. The annotations encompass intrapulmonary and extrapulmonary arteries and veins. All the annotations are performed by lung cancer expert surgeons, investing 2-3.5 hours for each image. It’s important to note that all patients in the dataset underwent lung cancer surgery, and these annotations have been effectively employed in clinical practice to support surgeons in planning such surgeries. For the sake of labeling efficiency, only vessels in the left or right lung with nodes were labeled. Consequently, most images have annotations for only half of the lung, while a few have labels for both sections.

Please send emails to me xiao.wei.xu@foxmail.com for the link and the password to download the dataset and the benchmark.
