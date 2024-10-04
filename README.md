GF Product Applicator - Step by Step
Overview
This web application helps users select the best product based on their needs through a step-by-step survey. The application reads two Excel files—one for the survey questions and another for product data. User responses are matched to specific product features, and the recommended products are displayed accordingly.
How to Use
1. Preparing Your Files:
  •	Question File (Survey): An Excel file containing survey questions and answer choices. The application will match the selected answer text directly to product features.
    o	This file should contain columns for ID, Question, Explanation, and multiple Answer and NextID pairs.
    o	You can always expand the answer choices by adding the columns following the format.
  •	Product File: An Excel file containing product data. The columns represent different product features, and the rows represent the products. Each value in these columns must match an answer from the survey.
    o	If a product can match multiple answers, you can enter the possible answers as a comma-separated list (e.g., 50-100,100-200). The application will consider the product as a match if any of the listed answers correspond to the user's selection.
    o	An empty cell is considered a match to any answer.
2. Upload the Files:
  1.	Click Choose Question File to upload the survey file.
  2.	Click Choose Product File to upload the product data file.
3. Answer the Questions:
  •	After uploading the survey file, the first question will be displayed.
  •	Choose an answer for each question. Based on your selection, the next question will dynamically appear.
  •	You can always change the answer of any answered questions, and the survey will adjust dynamically. 
4. View Product Recommendations:
  •	After completing the survey, the products that match your answers will be displayed.
  •	If no products match your selection, the application will notify you.
5. Clear All Answers:
  •	To reset the survey and start over, click the Clear All Answers button.
6. Limitations:
  •	For format reasons, avoid using numbers only as answers. For example, instead of using "3" as an answer, use "3." (with a period) to ensure proper matching.
