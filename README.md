# SCUT LFMB-3DFB Dataset
This repository is the Large-scale Finger Multi-Biometric database and benchmark for 3D Finger Biometrics (LFMB-3DFB) from paper:   
__LFMB-3DFB: A Large-scale Finger Multi-Biometric Database and Benchmark for 3D Finger Biometrics. 2021 IJCB Best Paper Award__  
By Weili Yang, Zhuoming Chen, Junduan Huang, Linfeng Wang and WenXiong Kang  


## Abstract
Fingers contain various discriminative biometric traits, such as fingerprint, finger vein, finger knuckle, finger shape, and so on, which are complementary in identity information. However, in most current research and practical applications, only one or a few traits are used, while others are ignored, resulting in degraded recognition performance and vulnerability to forgery. In this paper, we present the first attempt to collect and study all biometric traits on the finger. Firstly, a novel multi-view, multispectral 3D finger imaging system is created. To the best of our knowledge, it is the first biometric imaging system capable of capturing almost all finger-based traits. We scanned numerous fingers with this 3D finger imaging system, obtaining external skin images and internal vein images from 6 different views. The proposed 3D finger reconstruction and texture mapping algorithms are then used to generate 3D finger models with skin and vein textures. Second, we establish a benchmark dataset, namely the Large-scale Finger Multi-Biometric database and benchmark for 3D Finger Biometrics (LFMB-3DFB). The LFMB-3DFB contains 695 fingers, and each finger is acquired 10 times, yielding 6 finger skin images and 6 finger vein images, for a total of 83,400 images and 6,950 3D finger models. Finally, we design a more scientific and comprehensive evaluation protocol to conduct extensive experimental research and analysis on this database for both subject-independent verification and subjectindependent close-set identification tasks. Comprehensive and rigorous experiments for 2D finger traits recognition, multiview finger traits recognition, 3D finger traits recognition, and score-level fusion on LFMB-3DFB are carried out, and excellent results are achieved. The LFMB-3DFB database will be released at https://github.com/SCUT-BIP-Lab/LFMB-3DFB to promote 3D finger multi-biometric research using cutting-edge imaging techniques.



## SCUT LFMB-3DFB Dataset
**the Large-scale Finger Multi-Biometric database and benchmark for 3D Finger Biometrics (LFMB-3DFB)**
For subsequent studies to compare recognition algorithms in the same setting, please strictly follow the evaluation protocols in the benchmark (see Section BENCHMARK EVALUATION in the paper for details), Here we provide the record files for the division of the training set, validation set, and testing set, as well as the inter- and intra-class pairs files for the validation and testing sets.


--__dataset_partition_csv/training_set.csv__: the finger data in training set.
--__dataset_partition_csv/validation_set_inter-&intar-class pairs.csv__: the inter-&intar-class pairs in validation set, and the finger data in validation set are also these names in this file.
--__dataset_partition_csv/testing_set_inter-&intar-class pairs.csv__: the inter-&intar-class pairs in testing set, and the finger data in testing set are also these names in this file.

--__datasamples__: data samples provided to understand this dataset in detail.  
--__datasamples/LFMB-3DFB_Pictures_Seged_Rectified__: each capture get 6 raw images by the 6 different views of the imaging system, and we rectified and segmented the finger.   
--__datasamples/Deformed_Meshes_cylinder382_textured__: reconstructed 3D holographic finger models with textures with 382 vertices.  
--__datasamples/Deformed_Meshes_cylinder662_textured__: reconstructed 3D holographic finger models with textures with 662 vertices. 
--__datasamples/Deformed_Meshes_cylinder1022_textured__: reconstructed 3D holographic finger models with textures with 1022 vertices. 
--__datasamples/Deformed_Meshes_cylinder2602_textured__: reconstructed 3D holographic finger models with textures with 2602 vertices. 
--__datasamples/Deformed_Meshes_cylinder5543_textured__: reconstructed 3D holographic finger models with textures with 5543 vertices. 
--__datasamples/Deformed_Meshes_cylinder10064_textured__: reconstructed 3D holographic finger models with textures with 10064 vertices. 

## Request
The __SCUT LFMB-3DFB Dataset__ is publicly available(free of charge) to the research community. Unfortunately, due to privacy reasons, we cannot provide the database for commercial use.

We have made part of the dataset available for download in the repo in order to get a detailed view of this data. Those interested in obtaining the whole __SCUT LFMB-3DFB Dataset__ should download [release agreement](https://github.com/SCUT-BIP-Lab/SCUT-LFMB-3DPVFV/blob/main/SCUT%20LFMB-3DPVFV%20Database%20Release%20Agreement.docx), and send by e-mail one signed and scanned copy to scutbip@outlook.com.


While reporting results using the __SCUT LFMB-3DFB Dataset__, please cite the following article:    

@inproceedings{yang2021lfmb,
  title={LFMB-3DFB: A Large-scale Finger Multi-Biometric Database and Benchmark for 3D Finger Biometrics},
  author={Yang, Weili and Chen, Zhuoming and Huang, Junduan and Wang, Linfeng and Kang, Wenxiong},
  booktitle={2021 IEEE International Joint Conference on Biometrics (IJCB)},
  pages={1--8},
  year={2021},
  organization={IEEE}
}

@article{yang2022anovel,
  title={A Novel System and Experimental Study for 3D Finger Multi-Biometrics},
  author={Yang, Weili and Chen, Zhuoming and Huang, Junduan and Kang, Wenxiong},
  journal={IEEE Transactions on Biometrics, Behavior, and Identity Science},
  volume={},
  number={},
  pages={},
  year={2022},
  publisher={IEEE}
}


## Contact
Weili Yang   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology    
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641   
yang.wei.li@aliyun.com 



Prof. Kang Wenxiong   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology   
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641      
auwxkang@scut.edu.cn   
