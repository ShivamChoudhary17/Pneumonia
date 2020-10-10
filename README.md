# Pneumonia

> - __________________________________________________________________________________________________________________________________________________________________________

   ![Pneumonia](https://i.imgur.com/jZqpV51.png)
   
> - _________________________________________________________________________________________________________________________________________________________________________


### Content
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category ( **Pneumonia/Normal** ). *There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).*

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.


> - _____________________________________________________________________________________________________________________________________________________________________________

### [DataSet](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia?)

![A](data:image/png;base64,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)

> - _____________________________________________________________________________________________________________________________________________________________________________


![Image](https://www.medica-tradefair.com/medicacache/pica/7/2/8/7/9/0/1/111231588660476/asociaci-n-ruvid-halbe_breite-01-asociaci-n-ruvid-ray20comparison.jpg)
