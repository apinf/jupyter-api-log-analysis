[![Binder](http://mybinder.org/badge.svg)](https://hub.binder-beta.omgwtf.in/user/70933706-099c-418a-b478-e809e4c6edb0/notebooks/API_log_analysis.ipynb?)

# Jupyter Notebook - API log analysis
A Jupyter Notebook for analyzing log files from API Umbrella.

# Try it out
You can [view this notebook online](https://github.com/apinf/jupyter-api-log-analysis/blob/master/API_log_analysis.ipynb).

# Run locally

## Prerequisites
You will need to be familiar with Python and how to create virtual environments.

## Setup
To set up a local environment and run these notbooks, follow these steps:

1. Create and activate a virtual environment
2. Run `pip install -r requirements.txt`
3. If you want to run the Elasticsearch notebook
  - create an environment variable called `ELASTICSEARCH_URL` with the URL to an Elasticsearch instance
  - On GNU/Linux: `export ELASTICSEARCH_URL="http://example.com"
4. Run `jupyter notebook`
5. Navigate to the desired notebook and run the cells
