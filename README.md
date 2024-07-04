# Coding Exercises Inspired by Enderton's Mathematical Introduction to Logic

Davey Proctor

Reach out to me on [Linked In](https://linkedin.com/in/daveyproctor), or make a pull request!

## Introduction

Herbert B. Enderton wrote the standard university [textbook](https://www.amazon.de/-/en/Herbert-B-Enderton/dp/0122384520) on mathematical logic. 
At Yale I worked through this dense and enlightening work with the help of the remarkable professor [Sun-Joo Shin](https://philosophy.yale.edu/people/sun-joo-shin).
I invented these coding exercises as a bit of enrichment material to the textbook.

## How to use

1. Clone the repo: `git clone https://github.com/daveyproctor/mathematical_logic.git`

2. `docker-compose up --build -d`

3. visit http://localhost:<JUPYTER_PORT>/tree in the browser, where you should replace <JUPYTER_PORT> with its value from .env (currently 8891)

4. Paste the value for JUPYTER_TOKEN in the top box, also defined in the .env file. Current value is mytoken.

5. Try the example notebooks:
  * [source/notebooks/Sentential_Logic.ipynb](https://github.com/daveyproctor/mathematical_logic/blob/main/source/notebooks/Sentential_Logic.ipynb): 
    - P. 41 of Enderton presents "an algorithm" for parsing well formed formulas. This notebooks presents an implementation of the algorithm.
    - P. 42 Enderton - Polish Notation
    - P. 33 Enderton related to "satisfies"
    - P. 38 ex. 9. Sigma1 is equivalent to Sigma2 iff for any wff alpha, Sigma1 taut implies alpha iff Sigma2 taut implies alpha. Sigma is independent iff no member of Sigma is taut impled by the remaining members of Sigma.
    - a Context Free Grammar for parsing Sentential Logic, using nltk Python library.
    - Enderton 1.4 ex. 4: Unique readablity in English: "either ... or", "both ... and", "if ... then".
  * [source/notebooks/First_Order_Logic.ipynb](https://github.com/daveyproctor/mathematical_logic/blob/main/source/notebooks/First_Order_Logic.ipynb).
    - a Context Free Grammar for parsing First Order Logic.
    - (more to come!)