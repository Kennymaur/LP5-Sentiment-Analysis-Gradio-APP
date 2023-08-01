# LP5-Sentiment-Analysis-Gradio-APP

Project Structure
The Project proceeded in the following steps:
Data Acquisition. The data was made available in a Zindi Africa Challenge template.
The dataset had four columns: tweet id, safe_text, label, and agreement column.
The safe_text was the primary feature for our model, with the label being our target output.

Exploratory Data Analysis. As expected, the data had to be thoroughly explored to understand its content, identify missing values, distribution among others.
More so, because it was a classification task there was need to investigate label or target balance, its distribution among others which would subsequently inform what SMOTE technique to employ. 
After exploring the data, processing the data began.

 Fine-Tuning Pretrained Models. On hugging faces, we identified three pretrained models for text classification with similarities to the task that we had at hand.
 
