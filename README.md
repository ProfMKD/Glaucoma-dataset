# Glaucoma-dataset
glaucoma dataset - Labelled data for fundus images. 
Dataset for Glaucoma Diagnosis

This repository makes available the source code and the dataset for the works: 
1.	Anushikha Singh, Malay Kishore Dutta, M.ParthaSarathi, Vaclav Uher and Radim Burget, “Image processing based automatic diagnosis of glaucoma using wavelet features of segmented optic disc from fundus image”  Computer methods and programs in biomedicine, Vol. 124, pp. 108–120, Feb. 2016, doi: 10.1016/j.cmpb.2015.10.010.

2.	Ashish Issac, M.Partha Sarathi and Malay Kishore Dutta, “An adaptive threshold based image processing technique for improved glaucoma detection and classification” Computer methods and programs in biomedicine, Vol. 122 No. 2, pp. 229-244, Nov. 2015, doi: 10.1016/j.cmpb.2015.08.002. 

Data Collection: The digital colored fundus images used for the proposed work have been collected from Venu Eye Institute and Research Centre (VEIRC), New Delhi, India. The fundus images used for experimentation purpose are from patients in the age group of 18 to 75. The images have been labeled by the ophthalmologists and used anonymously. The hospital committee has provided an ethical clearance to use the images for research purpose. 
Camera and image details: The anterior and posterior region of the eye has been digitally photographed using a high-resolution Fundus Camera. A Welch Allyn Pan Optic Ophthalmoscope has been used for image acquisition. The fundus camera weighs 48lbs and is 5.12 inches long, 1.40 inches broad and 3.75 inches high. The camera can capture images with a 25º (for Glaucoma) field-of-view (FOV) which are stored in JPEG format and have a resolution of 2544 × 1696 pixels. This fundus camera is easy to use and has been used by the ophthalmologists to monitor the progression of ocular diseases like Glaucoma, Diabetic Retinopathy, Diabetic Macular Edema, etc.
Clinical Significance of the Database: The human fundus images, consists of many objects, however, for Glaucoma inspection, the optic disc region and its surrounding regions are clinically significant. The optic disc is the brightest circular / elliptical region present in the fundus image. The optic disc is the region from where the blood vessels exits the eye and forms the optic nerve. So, in the disc region, the blood vessels start to bend. This bending is an important parameter in deciding if the patient is suffering from Glaucoma. The disc region is divided into 4 sectors, namely, Inferior, Superior, Nasal and Temporal. The ISNT rule is also a clinical parameter involved in Glaucoma diagnosis. Clinically, it has been observed that the blood vessels starts to bend more in the inferior and superior region for a Glaucoma affected person, which increases the vertical extent of the cupping inside the disc region. So, a medical indicator, vertical Cup-to-disc-ratio (CDR) has been used to categorize the images in the current database. 
Database for Glaucoma Detection: The table summarizes the number of images and CDR range for all the three categories in the database.


Glaucoma Vertical CDR	>= 0.7,    Total Images:	32
Suspect Glaucoma Vertical CDR	0.4 – 0.7,  Total Images:107
Normal Vertical CDR	<= 0.4,  	Total Images:  225

License
Copyright (c) 2017-2020 Prof. (Dr.) Malay Kishore Dutta. The data can be used for only research Purpose and not for any commercial purpose. 

Citations
If you use this dataset in your work, then it is mandatory to cite the following papers. Else this will be considered as a violation. 

1.	Anushikha Singh, Malay Kishore Dutta, M.ParthaSarathi, Vaclav Uher and Radim Burget, “Image processing based automatic diagnosis of glaucoma using wavelet features of segmented optic disc from fundus image”  Computer methods and programs in biomedicine, Vol. 124, pp. 108–120, Feb. 2016, doi: 10.1016/j.cmpb.2015.10.010.
2.	Ashish Issac, M.Partha Sarathi and Malay Kishore Dutta, “An adaptive threshold based image processing technique for improved glaucoma detection and classification” Computer methods and programs in biomedicine, Vol. 122 No. 2, pp. 229-244, Nov. 2015, doi: 10.1016/j.cmpb.2015.08.002.


Acknowledgement
This work was supported in parts by the Grants from Department of Science and Technology (https://dst.gov.in/), Also the authors express their thankfulness to Dr. S.C. Gupta, Medical Director of Venu Eye research centre (https://www.venueyeinstitute.org/) for his contribution in classification of the images.

