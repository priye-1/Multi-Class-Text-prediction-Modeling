# Data Science Homework Test

To learn more about how you work as a data scientist, we'd like to ask you to complete a homework test. The test is about building a statistical prediction model.

## Dataset
That dataset consists of 1 million English reviews of cosmetics products on online shops.

### Variables
- product_id (string): Unique identifier for each product
- brand (string): The brand that makes the product
- price_usd (float): The lowest price we have ever seen this product go for in any shop
- category (string): The product category in our category system (category-subcategory-subsubcategory)
- shop (string): Where the review was posted
- review_published (date): When the review was posted (date)
- review_text (string): What the customer said about the product
- review_title (string): An optional title that the customer added to their review
- review_rating (integer): Target variable, a rating from 1 to 5

### Download
We will send you the data in a separate email. The file is a compressed CSV (94mb).

## Goal
Predict the rating based on the other variables. Your model should output a number between 1 and 5. You can choose any type of model. Please split the data into a training set and test set. Please choose an appropriate metric to evaluate the model's performance on the test set.

## Evaluation criteria
We will evaluate your work based on these criteria:
- Use of appropriate metrics and statistical model
- Documentation and reproducibility of your project

**Model performance is less important than the clarity of your code and approach**. Fine-tuning is not required. There is no need to spend more than 4 hours on this task. It's ok to copy code from Stack Overflow and other sources. If you copy 3 or more lines of code, please indicate that you did so by adding the link as a comment.

If you run into hardware limitations you can draw a sample from the dataset and work with that. This will not have an impact on the evaluation.

## Answer format
- files belonging to your analysis in R or Python (script, notebook, other configuration files...)
- readme indicating how we can run the code and what performance your model achieved
