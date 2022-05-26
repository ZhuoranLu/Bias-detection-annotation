# Bias-detection-annotation
This is a repository for the data collected in the study "Towards Better Detection of Biased Language with Scarce, Noisy, and Biased Annotations".


Here attached a sample of the annotations made by subjects. Each row is an annotation on one piece of text.

| _id | workerID | prediction | label | stance | text | 
| -------- | ---------------------| -----------------------  | ------------| ----- | ---------- | ----------------- | 
| 22CeEjpsgia8wnYeL | worker33 | Biased | Non-biased | Democrats | Football supports Trump in its promotion of ...|



* `_id` Str. The unique ID for each annotation.
* `workerId` Str. The unique ID for each subject who participated the annotation.
* `prediction` Str. The subject's annotation of whether the text is Biased or Non-biased.
* `label` Str. The expert's annotation of whether the text is Biased or Non-biased.
* `stance` Str. Subjects' self-reported political leaning: (1) democrats (2) republican (3) neutral 



