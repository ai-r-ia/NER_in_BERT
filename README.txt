Instructions for running the ColabNotebook and code in the folder attached

The code provided in the colab notebook is for zero-shot, few-shot and finetuning. 

Please run the code given in the folder named NER_in_BERT for changing the hyperparameters, loss and optimizer and to analyze the results.

To run the code in the repository kindly run the following commands:

	pip install -r requirements.txt

	python run_ner.py --data_dir=data/ --bert_model=bert-base-cased --task_name=ner --output_dir=out_base --max_seq_length=128 --do_train --num_train_epochs 5 --do_eval --warmup_proportion=0.1

The number of epochs can be chandged using the command line arguments. 
To change the loss, optimizer and other hyperparameters, please make changes in the run_ner.py file. There are commented lines of code to assist in changing loss functions and optimizers.

