# Data Analyst Job Data Cleaning Project

This project involves cleaning a messy dataset containing untouched, unprocessed data analysis job postings directly scraped from Indeed and Glassdoor across Canada. 
The raw dataset has been created by Aman Bhattarai and acquired from [Kaggle](https://www.kaggle.com/datasets/amanbhattarai695/data-analyst-job-roles-in-canada/data?select=Cleaned_Dataset.csv)
The data is processed using Python and Pandas to make it suitable for analysis. 

## Features
- Handle missing values and incorrect entries
- Categorize job types: Remote, Hybrid, In-person
- Categorize seniority levels: Junior, Mid, Senior
- Fix special character issues in city names

## Installation
1. Clone this repository:  
    ```sh
    git clone https://github.com/PaulinaBakiewicz/DAjobs-cleaning.git
    ```
2. Navigate to the project folder:  
    ```sh
    cd DAjobs-cleaning
    ```
3. Install the required Python libraries:  
    ```sh
    pip install pandas
    ```
Note: I recommend encoding it in UTF-8 as it contains special characters from French. I opted not to do it in this project.

## Usage
1. Run the Jupyter Notebook to see the data cleaning steps.
2. Adjust the file path if you place the dataset in a different folder.
3. The cleaned dataset will be saved as `cleaned_data.csv`.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Contributing
Feel free to submit issues or pull requests. Contributions are welcome! 

## License
Code in this project is licensed under the MIT License.

