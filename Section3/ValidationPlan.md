# Clinical Validation

## What is the intended use of the product?

The intended use for the presented product is to provide auto-computed information on the hippocampal volume to the clinicians.

## How was the training data collected? 

The training data was collected from users of different characteristics that participated in this project in exchange for rewards such as Amazon gift cards. This, thanks to the unlimited budged that our facility has. Furthermore, the data collected was obtained in the form of fMRI images, during different cognitive experiments that could help us to determine different diseases such as Parkinson or Alzheimer. More information about the characteristics of the obtained data can be found on the webpage of our institute with unlimited budget.

## How did you label your training data?

The data was labelled from apriori information from participant affected by different conditions. Nonetheless, different signal processing techniques were implemented in order to understand how the condition affected the cognitive function of the participants, techniques such as partial coherence, wavelets and many others. Nonetheless, the cognitive functionality was complemented from neuroscientists specialists diagnostics that provided the ground truth or labels for the participants' data.

## How was the training performance of the algorithm measured and how is the real-world performance going to be estimated?

The performance of the algorithm is measured using the DICE and Jaccard similarities with the ground truth. Moreover, its performance in the real world needs to be complemented with the analysis of experts. The method was developed to be used as a complement to neuroscientists conclusions.

## What data will the algorithm perform well in the real world and what data it might not perform well on?

The algorithm can be used on fMRI images stored in DICOM files. To be more specific, in DICOM files in which were used the HippoCrop tool to select the region of interest that was used to train the method. 