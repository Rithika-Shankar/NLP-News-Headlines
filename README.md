# News Headlines NLP and NER

## Description
This project applies **Natural Language Processing (NLP)** and **Named Entity Recognition (NER)** techniques using **spaCy** to extract key entities from news headlines. The project reads data from a CSV file containing scraped news headlines and identifies entities such as people, organizations, and locations. The structured entities provide insights from unstructured text data.

## Installation
1. Ensure you have Python installed on your machine.
2. Install the required libraries:
   ```bash
   pip install spacy pandas
   python -m spacy download en_core_web_sm

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Rithika-Shankar/news-headlines-nlp.git
2. Navigate to the project directory:
   ```bash
   cd news-headlines-nlp
3. Run the script:
   ```bash
   python nlp_entities.py
   
## Input
The script reads news headlines from a CSV file called news_headlines.csv, which should be generated from the News Headlines Scraping project. The file must contain a column labeled Headline.

## Output
The extracted entities are saved in a file called headline_entities.csv, which contains the following columns:

- Headline: The original news headline.
- Entities: A list of entities identified in the headline, including their types (e.g., PERSON, ORG, GPE).
  
## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- spaCy: For NLP and NER functionality.
- pandas: For data manipulation and storage
