# GSNet

## GSNet-based web application
To apply the GSNet model as a medical imaging tool, we have compressed the entire pipeline in an easy-to-use Web-based Application (Web App). This Web App takes in input as 3D MRI images in ‘.nii’ file format. With the input of FLAIR, t1, t1ce, and t2 MRI scans, our Web App can produce the corresponding segmentation masks for the Whole tumor, Tumor Core, and Enhancing Tumor regions, and further save them locally in ‘.nii’ file format within 20 seconds.
[![conducting a segmentation using the web app](https://img.youtube.com/vi/5vl5Yezn6C0/maxresdefault.jpg)](https://www.youtube.com/watch?v=5vl5Yezn6C0)
The Web App creates the outputs and saves them in any local folder. The corresponding indication is shown on the next page of the Web App. We have visualized the saved outputs using the software called ITK-SNAP.
[![visualizing the saved segmentation masks](https://img.youtube.com/vi/U09Ur23ldjM/maxresdefault.jpg)](https://www.youtube.com/watch?v=U09Ur23ldjM)
Due to the lightweight size, the Web App creates the segmentation masks very quickly. The weight file corresponding to this Web App is around 24.7 MB. The outputs which are saved as ‘.nii’ files are around 8 MB each so 24 MB in total (3 outputs for 3 separate regions).
