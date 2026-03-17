# Movie-Recommendation-system

## Problem Statement
Build a Recommender System to show personalized movie recommendations based on ratings given by a user and other users similar to them in order to improve user experience.

## Objectives
- Develop a recommendation system using:
  - Collaborative Filtering
  - Matrix Factorization
  - Content-Based Filtering
- Deliver personalized movie recommendations
- Enhance user experience through data-driven insights

## Tech Stack
* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Google Colab

## Models & Techniques Used
- Collaborative Filtering (User-based / Item-based)
- Matrix Factorization
- Content-Based Filtering
- XGBoost (for additional modeling/experimentation)
  
## Dataset
Dataset link : https://drive.google.com/drive/folders/1qe3di-dDXC4uMZp8dGIv-J_bFHoKjrWi?usp=sharing

### USERS FILE DESCRIPTION

=========================================================================

User information is in the file "users.dat" and is in the following format:

UserID::Gender::Age::Occupation::Zip-code

All demographic information is provided voluntarily by the users and is not checked for accuracy.
Only users who have provided some demographic information are included in this data set.

Gender is denoted by a "M" for male and "F" for female

Age is chosen from the following ranges:

1: "Under 18"

18: "18-24"

25: "25-34"

35: "35-44"

45: "45-49"

50: "50-55"

56: "56+"

Occupation is chosen from the following choices:

0: "other" or not specified

1: "academic/educator"

2: "artist"

3: "clerical/admin"

4: "college/grad student"

5: "customer service"

6: "doctor/health care"

7: "executive/managerial"

8: "farmer"

9: "homemaker"

10: "K-12 student"

11: "lawyer"

12: "programmer"

13: "retired"

14: "sales/marketing"

15: "scientist"

16: "self-employed"

17: "technician/engineer"

18: "tradesman/craftsman"

19: "unemployed"

20: "writer"

### MOVIES FILE DESCRIPTION

=========================================================================

Movie information is in the file "movies.dat" and is in the following format:

MovieID::Title::Genres

Titles are identical to titles provided by the IMDB (including year of release)

Genres are pipe-separated and are selected from the following genres:

Action

Adventure

Animation

Children's

Comedy

Crime

Documentary

Drama

Fantasy

Film-Noir

Horror

Musical

Mystery

Romance

Sci-Fi

Thriller

War

Western
