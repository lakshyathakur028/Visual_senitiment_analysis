To obtain a dataset, place two files, gen_img.py and save_img.py, within the same directory.

To initiate the process, open your terminal and execute the command "python3 gen_img.py class_name size_of_data_set". This command will generate a CSV file named class_name_urls.csv within the directory, containing links to images.

Next, execute the command "python3 save_img.py class_name_urls.csv" in the terminal. This will prompt the program to create a folder named class_name in the same directory. Inside this folder, you'll find the downloaded images.

Please note that the number of images downloaded might be fewer than the specified size_of_data_set due to the presence of corrupted images.

![267624940-012e5c59-bc4e-41f5-8f90-19f96dcb046e](https://github.com/lakshyathakur028/Visual_senitiment_analysis/assets/139463159/e41ba601-2254-431d-a828-7a524aee9c7d)
