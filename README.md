
<h3 align="center">Shared Task on "Detection and Extraction of Food Recalls and Foodborne Disease Outbreaks in Online News Articles"</h3>


## Background

Foodborne diseases and food recalls are major public health concerns, with outbreaks causing significant illness, and recalls aiming to prevent further harm to consumers. This shared task focuses on the development of automated systems for detecting foodborne disease outbreaks and recall events from news articles, particularly those in the form of FDA press releases.



### Task Description

This shared task consists of two subtasks. Given a news article:

* Subtask-1:(A multi-class classification task):
Participants will build a model that classifies the news article into one of three categories: (1) Food Recall, (2) Foodborne Disease Outbreak, or (3) Neither.

* Subtask-2 (Entity and Event Extraction): Participants will develop a system that extracts key entities and events from the article, including:

	* Target Organization (e.g., company or regulatory body involved in the incident or whose product has been recalled)
	* Product Name (e.g., food item being recalled or related to an outbreak)
	* Cause of Incident (e.g., primary cause of the food safety incident)
	* Disease Caused (e.g., diseases or health conditions caused by the incident)
	* Number of People Affected (e.g., how many individuals have been reported affected by the recall or outbreak)
	* Location (e.g., geographical location where the incident took place)

### Dataset

The dataset will consist of English-language news articles, press releases, and other publicly available documents related to foodborne diseases and recalls. The articles will be sourced from a combination of FDA press releases, news websites, and scientific publications. The training, development, and test sets contain 3,172 news articles, 357 news articles, and 1,005 news articles, respectively. The data is provided in XLSX format. Each article includes an ID, article categories (label for Subtask-1), and six entities mentioned in the article (for Subtask-2), as shown below. If any of the entities are not mentioned in the article, "N/A" is used in place of the entity.

### Evaluation Metrics:

* Subtask-1 (Multiclass Classification): Submissions will be ranked based on the Accuracy, weighted average Precision, Recall, and F1-score.
* Subtask-2 (Entity Extraction): Evaluation will be based on the percentage of correctly extracted entities for each entity type (e.g., Organization, Product, Cause, Disease, Number of People Affected, Location), as well as the overall accuracy of event extraction.

For further details see [Codalab] (https://codalab.lisn.upsaclay.fr/competitions/22154) competition page.
