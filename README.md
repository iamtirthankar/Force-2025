**Shared Task on "Foodborne Disease Outbreak and Recall Event Extraction from News" A multi-class classification task
**

**Background: **
Foodborne diseases and food recalls are major public health concerns, with outbreaks causing significant illness, and recalls aiming to prevent further harm to consumers. This shared task focuses on the development of automated systems for detecting foodborne disease outbreaks and recall events from news articles, particularly those in the form of FDA press releases.


Objective:
The task will allow researchers and practitioners to explore the capabilities of NLP in real-world, unstructured data extraction, specifically aimed at improving public health responses and consumer safety. Participants will be tasked with addressing two sub-tasks:
Task-1 (A multi-class classification task): Participants will build a model that classifies news articles into one of three categories: (1) Food Recall, (2) Foodborne Disease Outbreak, or (3) Neither.
Task-2 (Entity and Event Extraction): Participants will develop a system that extracts key entities and events from text, including:
Target Organization (e.g., company or regulatory body)
Product Name (e.g., food item being recalled or related to an outbreak)
Infection Name (e.g., the disease responsible for the outbreak)
Safety Incident (e.g., contamination or allergic reaction)
Number of People Affected (e.g., how many individuals have been reported affected by the recall or outbreak)

Data:
The dataset will consist of English-language news articles, press releases, and other publicly available documents related to foodborne diseases and recalls. The articles will be sourced from a combination of FDA press releases, news websites, and scientific publications. These documents have been annotated to highlight relevant events, entities, and categories.

Evaluation Metrics:
Task-1 (Classification): Accuracy: The proportion of correctly classified sentences out of the total number of sentences; Precision, Recall, and F1-score: Calculated for each of the three categories (Recall, Outbreak, Neither).
Task-2 (Entity and Event Extraction): Precision, Recall, and F1-score: For each type of entity (e.g., Product Name, Target Organization, Infection Name, etc.), as well as for the overall event extraction (including the relations between entities); Exact Match: An evaluation based on the percentage of correctly extracted entities and events, with the exact match between the predicted and true entities being counted.
