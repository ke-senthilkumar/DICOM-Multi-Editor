# DICOM-Multi-Editor
Sometimes its necessary to change some of the DICOM tags like Patient Name, ID, Date of Birth, Study Instance ID, Series Instance ID, Operator Name, Machine Name, Approval Status from Approved to UnApproved, etc. This program helps to modify these tags in dicom files from a folder. The output is modified and copied to another chosen folder. 
Its important to note that, no Linac data is modified other than the serial number or name. Gantry, Collimator, Couch or MLC data are not touched in anyway since these might affect the function itself.

The need for modifying these data is copying a set of data into same TPS by changing the Series/Study Instance ID, copying the data from one Linac to another Linac but TPS import doesn't allow because of serial number mismatch, etc.

Easy to use the program and screenshot given below.

<img width="690" height="589" alt="image" src="https://github.com/user-attachments/assets/b29fe388-ed4e-48b9-86d8-72a8801a1b3e" />


