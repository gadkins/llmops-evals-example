# Automated LLM Evals with CircleCI

This repo, along with [this notebook (graysonadkins.com)](graysonadkins.com/notebooks/evals/automated-llm-evals-with-circleci), demonstrate how to configure automated evals of language models using LangChain and CirclCI pipelines.

The repository consists of  

- `.circleci/config.yml` - A configuration file used by CircleCI for triggering the evals to run automatically on each commit  
- `app.py` - A knowledge base the LLM can use for generating quizzes  
- `test_assistant.py` - A collection of rules-based evals  
- `test_release_evals.py` - The model-graded evals configuration functions  
