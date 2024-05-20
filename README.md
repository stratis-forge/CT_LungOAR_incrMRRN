# CT_LungOAR_incrMRRN
This repository provides pre-trained deep learning models for segmenting the organs at risk in radiotherapy treatment planning
of lung cancer patients. It operates on axial CT scans acquired for this purpose in the head-first supine (HFS) orientation.  
  
Segmented structures:  
*  Right lung
*  Left lung
*  Heart
*  Esophagus
*  Cord
*  Proximal bronchial tree


  
## Installing dependencies  
Dependencies specified in `requirements.txt` may be installed as follows:  
  
````
conda create -y --name CT_LungOAR_incrMRRN python=3.5
conda activate CT_LungOAR_incrMRRN
pip install -r requirements.txt  
````
  
## Applying the model  
```  
python run_inference_nii.py <input_nii_directory> <output_nii_directory>  
```
A Jupyter [notebook](https://github.com/cerr/pyCERR-Notebooks/blob/main/autosegment_CT_Lung_OARs.ipynb) demonstrating how to run the model and visualize auto-segmented structures is provided.
  
## Citing this work
Um, H., Jiang, J., Thor, M., Rimner, A., Luo, L., Deasy, J. O., & Veeraraghavan, H. (2020). Multiple resolution residual network for automatic thoracic organs-at-risk segmentation from CT. *arXiv preprint arXiv:2005.13690*. https://doi.org/10.48550/arXiv.2005.13690
  
## License
By downloading the software you are agreeing to the following terms and conditions as well as to the Terms of Use of CERR software.

    THE SOFTWARE IS PROVIDED "AS IS" AND CERR DEVELOPMENT TEAM AND ITS COLLABORATORS DO NOT MAKE ANY WARRANTY, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, NOR DO THEY ASSUME ANY LIABILITY OR RESPONSIBILITY FOR THE USE OF THIS SOFTWARE.
        
    This software is for research purposes only and has not been approved for clinical use.
    
    Software has not been reviewed or approved by the Food and Drug Administration, and is for non-clinical, IRB-approved Research Use Only. In no event shall data or images generated through the use of the Software be used in the provision of patient care.
    
    You may publish papers and books using results produced using software provided that you reference the appropriate citations (https://doi.org/10.1016/j.phro.2020.05.009, https://doi.org/10.1118/1.1568978, https://doi.org/10.1002/mp.13046, https://doi.org/10.1101/773929)
    
    YOU MAY NOT DISTRIBUTE COPIES of this software, or copies of software derived from this software, to others outside your organization without specific prior written permission from the CERR development team except where noted for specific software products.

    All Technology and technical data delivered under this Agreement are subject to US export control laws and may be subject to export or import regulations in other countries. You agree to comply strictly with all such laws and regulations and acknowledge that you have the responsibility to obtain such licenses to export, re-export, or import as may be required after delivery to you.




