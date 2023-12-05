# NYU-MLCS-Backdoor-Attacks
 Repo for NYU's Machine Leraning for Cyber Security course assignment 'Backdoor Attacks' by Amrutha Patil (ap7982)

### Running the Code
To execute this code, open and run the Lab4_ap7982.ipynb file in a Jupyter Notebook environment. We recommend using a local Jupyter Notebook setup due to the substantial storage and RAM requirements, which might exceed the capabilities of basic platforms like Google Colab.

### Data and Model Location
The data and BadNet model are stored within the Lab4 folder. Please ensure that the paths to these resources are correctly specified in the code to enable seamless execution. \
\
Lab4: \
├── data: \
│   ├──── cl: \
│   │   ├────── valid.h5 \
│   │   └────── test.h5 \
│   └──── bd: \
│       ├────── bd_valid.h5 \
│       └────── bd_test.h5 \
├── models: \
│   ├──── bd_net.h5 \
│   └──── bd_weights.h5 

### Instructions
- Launch a Jupyter Notebook environment.
- Open the Lab4_ap7982.ipynb file.
- Ensure the file paths for data and models within the Lab4 folder are accurately set in the code to avoid any path-related issues.
- Execute the code cells in sequence to observe the results.

### Dependencies
Ensure all necessary dependencies, such as Python libraries (e.g., NumPy, Pandas, Matplotlib, seaborn, etc.) and machine learning frameworks (e.g., TensorFlow, Keras), are installed in your environment before running the code.

### Outputs
The saved models for repaired networks for X={2%,4%,10%} are available in the main repo under names 'repair_network_2.h5', 'repair_network_4.h5', and 'repair_network_10.h5' respectively.
