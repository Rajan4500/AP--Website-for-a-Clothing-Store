ASSIGNMENT 3 – MILESTONE II
Clothing Shopping and Review Recommendation Website

Student Number: S4225218

PROJECT DESCRIPTION
This project is a clothing shopping website developed using Python and Flask. Customers can browse clothing products, search by category, view product details and submit reviews.

The website uses a Logistic Regression classification model trained in Milestone I to predict whether a customer recommends a clothing item.

HOW TO RUN THE WEBSITE
1. Open the project folder in VS Code.
2. Open a terminal in the project directory.
3. Install the required packages if they are not already installed:

   pip install flask pandas scikit-learn beautifulsoup4

4. Run the application:

   python main.py

5. Open the following URL in a browser:

   http://127.0.0.1:5000

IMPORTANT DETAILS
- main.py is the main Flask application file.
- The clothing dataset is located in the data folder.
- The trained classification model, vectorizer and preprocessing files are stored in the models folder.
- The model generates a binary recommendation: 1 = Recommended, 0 = Not Recommended.
- Customers can override the predicted recommendation before saving.
- Confirmed reviews are saved as individual HTML files in the saved_reviews folder and can be accessed through unique URLs.
- The search supports similar keyword forms, such as "dress" and "dresses".
- Customer login is not required.

Video demostration link: https://rmit-arc.instructuremedia.com/embed/864c65f6-aa28-4a27-9908-20ec2c5383ed

END OF README