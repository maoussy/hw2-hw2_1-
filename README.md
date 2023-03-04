#Step to follow:


Clone the repository


For training, make sure that, ModelSaveLoc = "TrainedModels" in the main_execution() function in the Videocaptioning_main.py (set as default). Models in this version is executed for 20 epochs


Before running the bash script "hw2_seq2seq.sh", check the "main" function and please make sure that, train = False, test=True are given.


For testing, make sure that, ModelSaveLoc = "BestModel" in the testmodel() function in the Videocaptioning_main.py (set as deafult), and then run the bash script named "hw2_seq2seq.sh" with "testing_data" and result3.txt. (During Testing)



Bleu Score for top 5 models are given in the file named "final_result.csv

The top model:

model_batchsize_32_hidsize_128_DP_0.2_worddim_2048.h5 (Bleu Score - 0.699341592)



