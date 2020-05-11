# imagenet-gpu-test
Testing Load and Run Time of P40, K80 and GCP JupyterHub GPUs


# Run
Compatibility - python 3.6, torch 1.5
1) Download dataset 
	!wget http://cs231n.stanford.edu/tiny-imagenet-200.zip
	!unzip tiny-imagenet-200.zip

2) Load cuda modules and change venv name to personal venv with dependencies installed (update in shell script) 
3) Check model name and hyper parameters
4) Schedule Jobs on specific gpu (launch_k80.s, launch_p40.s)
5) View Output File for logs. Best checkpoint of model will be saved

