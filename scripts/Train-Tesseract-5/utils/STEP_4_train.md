## Extracting .lstm from .traineddata
combine_tessdata -u /path/to/tessdata/hin.traineddata lstm_model/hin.lstm

## Training Command
lstmtraining --model_output fine-tuned --continue_from lstm_model/san.lstm --traineddata ../Tesseract_4/pre_trained_weights/san_iitb.traineddata --train_listfile train.txt --max_iterations 400

## Create .traineddata for Your Fine-Tuned Model
lstmtraining --stop_training --continue_from /path/to/checkpoint --traineddata /path/to/your/traineddata/lang.traineddata --model_output /path/to/output/lang_finetuned.traineddata

## Eval Command
lstmtraining  --continue_from fine-tuned_checkpoint --traineddata san_finetuned.traineddata --train_listfile train.txt --eval_listfile train.txt --max_iterations 0