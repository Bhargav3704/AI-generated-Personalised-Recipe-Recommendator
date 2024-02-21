# AI generated personalized Recipe Recommendator
This Python application streamlines the grocery shopping process for home cooks by generating comprehensive ingredient lists for any given dish. Users input the dish name, and the program fetches detailed ingredient information, including the top options available on Ocado based on factors like price, customer ratings, and review counts. By utilizing web scraping, data cleaning, and analysis techniques, this tool delivers actionable insights to enhance the efficiency and cost-effectiveness of grocery shopping.
# Features
-Utilizes OpenAI's language model to fetch ingredients for a specified dish.
-Scrapes Ocado to gather price, link, rating, and review count data for each ingredient.
-Analyzes and filters the collected data to select the best product options.
-Generates a clean and concise summary for easy decision-making based on the analysis.
# To begin with
Python 3.6+
OpenAI API Key
Required Python packages: `requests`, `beautifulsoup4`, `pandas`
# What is needed
## Clone the repository to your local machine:
```bash
git clone 
```
```bash
pip install -r requirements.txt
```
# Configuration
Create a `.env` file in the project directory. Enter your OpenAI API key into the `.env` file as follows:
```bash
OPENAI_API_KEY=your_api_key_here
```
To ensure that the script reads the API key from the `.env` file, update the relevant code section.
# Usage
To use automated ingredient recommodator for the dish follow the steps:
```bash
python script.py
```
When asked, enter the name of the meal whose ingredients you want to analyse. The script will then generate a summary of the best possibilities for each ingredient based on the scraped information.
# Contribution
To contribute to Automated Ingredient Analyzer and Shopper, follow these instructions.
```bash
-Fork the repository.
-Create a new branch using the command: git checkout -b branch_name.
-Make changes to the code and commit them using: git commit -m 'commit_message'.
-Push the changes to the original branch using: git push origin Automated Ingredient Analyzer and Shopper/branch_name.
-Create a pull request to merge the changes into the main branch.
```
Alternatively, see the GitHub documentation on creating a pull request.
# License
This project is licensed under the MIT License - see the LICENSE file for details.
# Acknowledgments
Thank you, OpenAI, for sharing the GPT API. This initiative does not recommend any particular online food store.
