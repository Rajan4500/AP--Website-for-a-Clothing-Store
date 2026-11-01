# AP--Website-for-a-Clothing-Store

PROJECT OVERVIEW
This project is a clothing shopping website developed using Python and Flask.
Customers can browse clothing products by department, search for clothing
categories, view product details and existing reviews, and submit new reviews.

The website uses a Logistic Regression classification model trained during
Assignment 3 Milestone I to predict whether a written review recommends a
clothing item.

MAIN FEATURES
- Homepage with clothing product previews, images and descriptions.
- Department/category browsing and keyword search with matching-item counts.
- Search support for similar keyword forms, such as "dress" and "dresses".
- Product details pages with customer reviews.
- Review submission using a title, description and rating.
- Machine learning recommendation prediction: 1 = Recommended,
  0 = Not Recommended.
- Customer option to override the predicted recommendation before saving.
- Confirmed reviews saved as individual HTML files with unique URLs.
- Newly saved reviews displayed on the corresponding product details page.

HOW TO RUN
1. Open the project folder in VS Code or a terminal.
2. Use a Python environment with the required packages installed.
   Main packages used: Flask, pandas, scikit-learn and BeautifulSoup4.
   To install them, run:

   pip install flask pandas scikit-learn beautifulsoup4

3. From the project folder, start the website with:

   python main.py

4. Open this address in a web browser:

   http://127.0.0.1:5000/

IMPORTANT PROJECT FILES
- main.py: Main Flask application (run this file to start the website).
- app.py: Separate lecture demonstration file; not the clothing store entry point.
- data/assignment3_II (2)-1.csv: Clothing dataset.
- models/clothing_model.pkl: Trained classification model.
- models/clothing_vectorizer.pkl: Text vectorizer.
- models/clothing_preprocessing.pkl: Saved text preprocessing resources.
- templates/: HTML pages for browsing products and submitting reviews.
- static/: Website stylesheet and clothing images.
- saved_reviews/: HTML files generated when new reviews are confirmed.

HOW TO TEST
1. Browse products from the homepage or department navigation.
2. Search for a category such as "dress" or "dresses".
3. Select a product and open its details page.
4. Click "Add New Review" and enter a title, description and rating.
5. Click "Predict Recommendation" to view the model's prediction.
6. Accept or override the prediction and confirm the review.
7. Check the saved review URL and return to the product page to see the review.

NOTES
- The website runs locally using Flask.
- No customer login is required for this assignment.
- Product images are used for presentation purposes.
- The trained model and dataset files must be kept in their respective folders
  for the application to work.
