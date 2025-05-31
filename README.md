Generative AI-Powered Recommendation System for Personalized Ad Creatives

Overall Project Details:
This project develops a system to generate personalized ad creatives for e-commerce using generative AI. It centers on processing user interaction data to create targeted ad text and evaluating its effectiveness through click-through rate (CTR) improvements. The core components include:
Data Processing: Handling e-commerce user interaction data to prepare it for model input.

Ad Creative Generation: Using DistilBERT, a lightweight language model, to generate ad text tailored to user behavior.

CTR Evaluation: Assessing ad effectiveness via A/B testing to measure CTR improvements (target: 5–10%).

Deployment: Building a FastAPI endpoint to serve generated ad creatives for real-time use.

The project is implemented in Azure ML Studio’s Free Tier, leveraging Pandas for data processing, PyTorch for model development, and statistical methods for evaluation.

Dataset Details:
The project uses the RetailRocket E-Commerce Dataset, which contains user interactions from an e-commerce platform.
Source: Kaggle - RetailRocket E-Commerce Dataset

File Used: events.csv
Size: ~94.2 MB

Fields: 
timestamp: Event timestamp (Unix).

visitorid: Anonymized user ID.

event: Interaction type (view, addtocart, transaction).

itemid: Item ID.

transactionid: Transaction ID (NaN for non-purchases).

Records: ~2.75 million interactions.

Download Instructions:
Visit Kaggle link.

Sign in or create a Kaggle account.

Download events.csv (within dataset zip).

For Azure ML Studio:
Upload to default datastore: Data > Datastores > Default Datastore > Upload.

Place in UI/2025-05-31_184443_UTC/events.csv.

For local use:
Save events.csv in your project directory.

Update code to point to the file path.

