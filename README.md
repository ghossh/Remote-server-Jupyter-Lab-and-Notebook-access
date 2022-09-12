# Remote-server-Jupyter-Lab-and-Notebook-access

## To open Jupyter Notebook

### In your terminal :
ssh -L 8188:localhost:8188 remote_server_username@remote_server_ip

 
### type in remote server after login:
jupyter notebook --no-browser --port=8188

you can change 8188 port. 




## To open Jupyter Lab 

### In your terminal :
ssh -L 8188:localhost:8188 remote_server_username@remote_server_ip

### type in remote server after login:
jupyter lab --no-browser --port=8188

you can change 8188 port. 

