# Beer-Reviews

This project consists in the prediction of a quality score associated with a beer review. Practically, you
are required to build a regression model capable of inferring the quality score assigned to the beer by the
reviewer.


The dataset for this project contains beer reviews in tabular format. It counts 100,000 entries, each of
which corresponds to a review expressed by a user on a website for beer benchmarks.
Each review is characterized by both numerical and categorical attributes. Each reviewer evaluates
the beer on four different categories, namely appearance, aroma, palate and taste. A textual description
is provided as well. Additionally, several information on the user is included. The quality score is reported
on the feature named review/overall and is expressed as a number between 1 and 5. Half scores, such
as 1.5, 2.5, etc., are allowed. The dataset is located at:
https://dbdmg.polito.it/wordpress/wp-content/uploads/2021/06/DSL_project_2021.zip
Within the archive, you will find the following files:

• development.tsv (development set): a tab-separated values file containing the reviews from the
development set. This portion does have the review/overall feature, which you should use to train
and validate your models.

• evaluation.tsv (evaluation set): a tab-separated values file containing the reviews from the evaluation set. This portion does not have the review/overall feature.

• sample_submission.csv: a sample submission file.
