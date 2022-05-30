# Bias-detection-annotation
This is a repository for the data collected in the study "Towards Better Detection of Biased Language with Scarce, Noisy, and Biased Annotations".


Here attached a sample of the annotations made by subjects. Each row is an annotation on one piece of text.

| _id | workerID | textId | prediction | label | stance | leaning | text | 
| -------- | ---------------------| ------------- | -----------------------  | ------------| ---------- | ---------- | ----------------- | 
| 22CeEjpsgia8wnYeL | worker33 | 25 |  Biased | Non-biased | Democrats | left | Football supports Trump in its promotion of ...|



* `_id` Str. The unique ID of each annotation.
* `workerId` Str. The unique ID of each subject who participated the annotation.
* `textId` Int. The unique ID of the text annotated.
* `prediction` Str. The subject's annotation of whether the text is Biased or Non-biased.
* `label` Str. The expert's annotation of whether the text is Biased or Non-biased.
* `leaning` Str. The expert's annotation of whether the text is left-leaning or right-leaning.
* `stance` Str. The subject's self-reported political leaning: (1) democrats (2) republican (3) neutral 



