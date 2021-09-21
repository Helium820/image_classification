# object_detection

### requirements:  
Open-source API/frameworks for machine learning:  
- tensorflow, keras, PyTorch  

Useful library:  
- numpy, os, ...



### Inference test
Directory `inference_dir/` contains the elements needed for processing a quick detection with trained model by running jupyter notebook. 
An example has been done in `input/` and `output/` directories.

Download the pre-trained cloud-detection model:  
and put [Model link](https://drive.google.com/uc?id=1pekFSYzIDtVY15F9VJUVOtNXAr6oW5Dy&export=download) into `exported-models/$model_name+_ckpt-31/saved_model/` directory  
put [variables.data](https://drive.google.com/uc?id=1JOE_97jrEeUtTZqo3x62Qq0PspPmgRWy&export=download) and [variables.index](https://drive.google.com/uc?id=1Ph7c6v9q-sgEzZlmb9walaKBndzGbAzE&export=download) into `exported-models/$model_name+_ckpt-31/saved_model/variables/` directory 

