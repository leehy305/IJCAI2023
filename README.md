# IJCAI2023

Implementation for the experiments in " " paper, AI and Social Good, IJCAI 2023.


# Repository Structure and Code Breakdown
Chicago and Washington D.C. folder has same Repository Structure as follows:
1. code
   (1) utils.ipynb
      - 'utils.ipynb' file loads dataset and provide code for downstream application.
   (2) model.ipynb
      - 'model.ipynb' file is our model structure
   (3) main.ipynb
      - 'main.ipynb' file is run to train our model and shows the result of downstream task.
      - The downstream task is performed for all year. Therefore, we need to perform prediction task for each year. 
   
3. data
   (1) Downstream
      - income, poverty, education, unemployment, %white, %black, %hispanic
      - Chicago has the above dataset from 2013 to 2020 at community area level.
      - Washinton D.C. has the above dataset from 2013 to 2021 at census tract level.
   (2) graph
      - 'heterograph1320.bin' - multi-period Urban-HIN
      - 'heterograph{year}.bin' - urban-HIN for each year
   (3) mobility data
      - src_matrix for each year
      - dst_matrix for each year
