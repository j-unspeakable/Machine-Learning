https://www.kaggle.com/shashwatwork/dementia-prediction-dataset


Scope: Health and Medicare
Topic: Classification & Prediction of Dementia
Project Description:
The deterioration of cognitive function of a person is in some way, one of the many syndromes that one wouldn’t want to be
diagnosed with. The chances that a person will have dementia and the probable type they can have is what we aim to solve in this project.


Dataset Features:
It consists of 15 features which are described as follows:

Subject.ID - Unique Id of the patient.
MRI.ID - Unique Id generated after conducting MRI on patient.
Group - It is a group of Converted (Previously Normal but developed dimentia later), Demented and Nondemented (Normal Pateints).
Visit - Number of visit to detect dementia status.
MR.Delay - Not Known.

Demographics Info
M.F - Gender
Hand - Handedness (actually all subjects were right-handed so I will drop this column).
Age - Age in years.
EDUC - Years of education.
SES - Socioeconomic status as assessed by the Hollingshead Index of Social Position and classified into categories from 1 (highest status)
to 5 (lowest status).

Clinical Info
MMSE - Mini-Mental State Examination score (range is from 0 = worst to 30 = best).
CDR - Clinical Dementia Rating (0 = no dementia, 0.5 = very mild AD, 1 = mild AD, 2 = moderate AD).

Derived anatomic volumes
eTIV - Estimated total intracranial volume, mm3.
nWBV - Normalized whole-brain volume, expressed as a percent of all voxels in the atlas-masked image that are labeled as gray or
white matter by the automated tissue segmentation process.
ASF - Atlas scaling factor (unitless). Computed scaling factor that transforms native-space brain and skull to the atlas target
(i.e., the determinant of the transform matrix).