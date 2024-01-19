# VSS-FEDAVG

The user can successfully run the code by following these steps: 1. Create a folder named 'adaptive_synchronization' and place all the code from the project into this folder; 2. In the file 'datasource.py', modify the data download path in the function 'def get_datasets()' to the path where the data is located; 3. The user can modify hyper-parameters in the file 'worker_process_as.py', including the choice of data-model, the D_ALPHA value related to non-IID, synchronization frequency, input image dimensions (image_size), and the number of labels, etc.; 4. Modify the client's IP address in lines 4 and 5 of the file 'train.sh'; 5. After all modifications are complete, navigate to the 'adaptive_synchronization' folder in the command line and enter 'bash train.sh' to run the code.

Additionally, during the attempt to run the code, various errors may occur, such as missing necessary library files. For specific error messages and run results, please check the details in the Logs folder.
