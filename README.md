# IBM Article Recommendation System

This project builds several types of recommendation systems using real user–article interaction data from the IBM Watson Studio platform. It explores rank-based recommendations, collaborative filtering, content-based recommendations using NLP, and matrix factorization techniques to create personalized article suggestions.

## Getting Started

These instructions will help you set up the project on your local machine for development, testing, and exploration.

You should clone or download the project files, including:

- Recommendations_with_IBM.ipynb

- user-item-interactions.csv

- articles_community.csv

Make sure you are working inside a Python virtual environment.

### Dependencies

This project requires the following Python packages:

```
- numpy
- pandas
- scikit-learn
- matplotlib
- jupyter
```
You can install all dependencies via: 

```
pip install -r requirements.txt
```

### Installation

Follow these steps to set up your development environment:

1. Create a virtual environment

```
python -m venv nanodegree_prj4
```

2. Activate the environment
   
```
nanodegree_prj4\Scripts\activate # for windows
source nanodegree_prj4/bin/activate # for mac/linux
```

3. Install dependencies

```
pip install numpy pandas scikit-learn matplotlib jupyter
```

4. Generate a requirements file (optional)

```
pip freeze > requirements.txt
```

5. Launch Jupyter Notebook

```
jupyter notebook
```

6. Open the notebook:

```
Recommendations_with_IBM.ipynb
```

## Testing

Automated tests are provided directly inside the notebook. The test cells check if each required function behaves correctly.

To run tests:

- Open the notebook

- Run cells sequentially

- Look for outputs such as
```
   All tests passed!
```

### Break Down Tests

- Part I Tests:
  - Validate data exploration values such as number of users, articles, interactions, etc.

- Part II Tests:
  - Ensure rank-based recommendation functions return correct article IDs and names.

- Part III Tests:
  - Confirm user–item matrix creation, similarity logic, and collaborative filtering recommendations.

- Part IV Tests:
  - Validate TF-IDF and KMeans clustering for content-based recommendations.

- Part V Tests:
  - Check the correctness of SVD decomposition and latent feature analysis.

These tests help guarantee correctness and reproducibility across student submissions.

## Project Instructions

1. Perform exploratory data analysis (EDA) on user–article interactions

2. Create rank-based (popularity) recommendations

3. Build a user–user collaborative filtering recommendation system

4. Implement a content-based recommender using TF-IDF and KMeans

5. Apply matrix factorization using SVD to generate latent features

6. Compare the different recommendation methods

7. Interpret results and discuss strengths, limitations, and potential improvements

Deliverables include:

- Fully executed Jupyter Notebook

- Completed functions for all recommendation methods

- Written explanations and analysis

- Final exported HTML notebook (via nbconvert)

## Built With

* [Python] - Core programming language used throughout the project
* [Jupyter Notebook] - Environment for interactive analysis
* [Pandas] - Data manipulation and preprocessing
* [Scikit-learn] - TF-IDF vectorization, clustering, and matrix operations
* [Matplotlib] - Visualizations
* [NumPy] - Numerical operations
* [IBM Watson Dataset] - Real-world interaction data powering the recommendation models
