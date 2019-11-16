# HighRES: Highlight-based Reference-less Evaluation of Summarization


## Getting HighRES running

0. Make sure you have `pipenv` and `yarn` installed. 
1. Clone this repo.
2. At the repo's root, run `yarn install` and `pipenv install`.
2. Open terminal at this repo's root directory. Run `yarn build` and then `yarn serve`.
3. Open another terminal window at the same location and run `export FLASK_APP='backend/app'` followed by `flask run`.

Now you should be able to go to `localhost:8080/admin` to start playing with the interface.

Note that this version of the repo has disabled the login screen completely, so do *not* deploy this online without re-enabling that.
