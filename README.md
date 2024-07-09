# generate-data


In this study to optimize the model DialogLED from: https://github.com/microsoft/DialogLM/tree/main/DialogLED

The AMI folder is the AMI conference dataset.

generation_data.json is the 61 meeting data we generated.

new_train.json is the 158 meeting data after merging AMI's train.json and generation_data.json.

weight_summarization.py is the code to train the DialogLED model using a weighted sampling strategy.

Repetition of this experiment according to the https://github.com/microsoft/DialogLM/tree/main/DialogLED code retrieval results first,
Now replace train.json with new_train.json for the AMI dataset. Simply replace run_summarization.py with weight_summarization.py while training. The other experimental environments remain unchanged.
