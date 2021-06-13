# TopoTxR: A Topological Biomarker forPredicting Treatment Response in Breast Cancer #

**Fan Wang, Saarthak Kapse, Steven Liu, Prateek Prasanna, Chao Chen, IPMI 2021.**  
Archive page (https://arxiv.org/abs/2105.06049)  
Paper (https://arxiv.org/pdf/2105.06049.pdf)

Characterization of breast parenchyma on dynamic contrastenhanced magnetic resonance imaging (DCE-MRI) is a challenging
task owing to the complexity of underlying tissue structures. Current quantitative approaches, including radiomics and deep learning models, do not explicitly capture the complex and subtle parenchymal structures, such as fibroglandular tissue. In this paper, we propose a novel method to direct a neural network’s attention to a dedicated set of voxels surrounding biologically relevant tissue structures. By extracting multi-dimensional topological structures with high saliency, we build a topology-derived biomarker, TopoTxR. We demonstrate the efficacy of TopoTxR in predicting response to neoadjuvant chemotherapy in breast cancer. Our qualitative and quantitative results suggest differential topological behavior of breast tissue on treatment-na¨ıve imaging, in patients who respond favorably to therapy versus those who do not.

<br/>
<p align="center"> 
<img src="pics/teaser.png" alt="drawing" width="100%"  />
</p>

<br/>
<p align="center"> 
<img src="pics/Picture1.png" alt="drawing" width="85%"  />
</p>

TopoTxR is tested under Windows 10 and ran on jupyter notebook with pytorch support.

### 1. Instructions ###
Before running the program, here are a few parameters you might want to change:
Archpool/return_settings():
- branch_name: the name of the pytorch log folder to put saved models
- continue_model: train from the saved checkpoint
- model_step: if continue_model is True, specifiy the step you want to to continue training from
- save_path: the path to put the pytorch log folder
- data_path: path to your training folder 1
- data_path2: path to your training folder 2

Go to Examples.ipynb and hit run button.
