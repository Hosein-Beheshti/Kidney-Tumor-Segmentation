# Kidney-Tumor-Segmentation
Implementing a 2D segmentation pipeline to segment kidneys and the tumors existing inside kidneys using CT images from KITS21 dataset and PyTorch.

I implemented the model in different planes: axial, coronal, and sagittal. We got the best result using the axial plane, with an average dice of 96.1% for kidney segments and 81.1 for tumors.

One example of segmentation done by our model for kidney and tumors are relatively shown below. The segments are displayed in red, and the edges of the annotations are specified in green.


<table>
  <tr>
    <td><img src="https://github.com/Hosein-Beheshti/Kidney-Tumor-Segmentation/blob/main/295_kidney_result2.png?raw=true" width="400"></td>
    <td><img src="https://github.com/Hosein-Beheshti/Kidney-Tumor-Segmentation/blob/main/295_Tumor_result2.png?raw=true" width="400"></td>
  </tr>
</table>




