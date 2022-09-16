# In-Context Learning
In-context learning is a mysterious emergent behavior in large language models (LMs) where the LM performs a task just by conditioning on input-output examples, without optimizing any parameters
# overview
This repository is used for week 4 challenge of 10Academy. The instructions for this project can be found in the challenge document.

Large Language Models coupled with multiple AI capabilities are able to generate images and text, and also approach/achieve human level performance on a number of tasks. The world is going through a revolution in art (DALL-E, MidJourney, Imagine, etc.), science (AlphaFold), medicine, and other key areas, and this approach is playing a role in this revolution.

### Project Structure
The repository has a number of files including python scripts, jupyter notebooks, raw and cleaned data, and text files. Here is their structure with a brief explanation.

### .dvc
Data Version Control configurations
### .github
a configuration file for github actions and workflow

### workflows/CML.yml continous machine learning configuration
### data
the folder where the raw, and cleaned datasets' csv files are stored
### notebooks
job_description_eda.ipynb: a jupyter notebook that Explanatory Data Analysis
job_description_context.ipynb: a jupyter notebook for testing different techniques using LLM
### scripts
Different python utility scripts that have different purposes.
### tests
root folder

### requirements.txt: a text file lsiting the projet's dependancies
.gitignore: a text file listing files and folders to be ignored

## README.md: Markdown text with a brief explanation of the project and the repository structure.
