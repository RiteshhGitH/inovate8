# Nex Resume Highlighter [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]

NEX Resume Highlighter is an automated solution designed to help both candidates and recruiters efficiently identify key information in resumes by highlighting relevant parts based on specific focus areas or skills.

## Table of Contents
- [Problem Statement](#problem-statement)
- [Solution Overview](#solution-overview)
- [Methodology](#methodology)
- [Implementation](#implementation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Problem Statement 🚀🚀

In today’s competitive job market, candidates often need to highlight specific keywords and experiences on their resumes to stand out to potential employers. However, manually identifying and emphasizing these keywords can be time-consuming and prone to bias. Even recruiters face challenges in quickly pinpointing specific details in resumes. The problem statement for this project is to develop an automated solution that highlights relevant parts of a resume based on given focus areas, allowing both candidates and recruiters to easily identify key information.

## Solution Overview

The solution involves utilizing Natural Language Processing (NLP) techniques to process resume documents, extract relevant keywords and entities, match them against given focus areas or skills, and highlight the relevant parts of the resume text. By automating this process, Resume Highlighter aims to streamline the evaluation of candidates and improve the efficiency of recruiters in identifying suitable candidates.

## Methodology

The methodology for developing Resume Highlighter includes:
- Data preprocessing to parse and tokenize resume documents.
- Keyword extraction using NLP techniques such as Named Entity Recognition (NER) and Part-of-Speech (POS) tagging.
- Focus area analysis to match extracted entities against given focus areas or skills and assign weights based on relevance.
- Highlighting the relevant parts of the resume text based on the assigned weights.
- Visualization or storage of the highlighted sections for easy reference by recruiters or candidates.

## Implementation

Resume Highlighter is implemented using Python programming language and popular NLP libraries such as spaCy and NLTK. The implementation includes modules for data processing, keyword extraction, focus area analysis, highlighting, and visualization. Additionally, a frontend interface is developed using Flask framework to display the highlighted sections of resumes.

## Usage

To use Resume Highlighter:
1. Clone the repository to your local machine.
2. Open the notebook in jypter notebook
3. Installl and check all the dependencies
4. Add the test resumes in json format in colab
5. Import the dataset and run the code


## Contributing

Contributions to Resume Highlighter are welcome! If you have suggestions for improvements, bug fixes, or new features, please open an issue or submit a pull request. For major changes, please discuss them in advance with the maintainers.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This project is licensed under the [MIT License](LICENSE).
