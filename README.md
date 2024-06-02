# Extractive and Abstractive Text Summarization for Tamil Language

## Project Description
This project focuses on developing and evaluating both extractive and abstractive summarization techniques for Tamil text. The aim is to create methods that can condense large volumes of text into concise summaries while retaining the essential information.

### Extractive Summarization
Extractive summarization involves selecting key sentences from the original text. This project implements three different extractive summarization methods:
- **Frequency Table Approach**: Scores sentences based on the frequency of words they contain.
- **Sentence Weighing Method**: Utilizes TF-IDF and other metrics to score sentences.
- **Sentence Clustering Method**: Uses K-Means clustering to group similar sentences and select representative sentences from each cluster.

### Abstractive Summarization
Abstractive summarization generates new sentences that convey the same meaning as the original text. This project fine-tunes three state-of-the-art models for abstractive summarization:
- **mT5**
- **mBART**
- **m2m100**

### Key Features
- **Data Collection and Preparation**: Processes and prepares Tamil text documents for summarization.
- **Evaluation Metrics**: Uses ROUGE metrics to assess the performance of summarization methods.
- **Visualization**: Provides visualizations such as t-SNE plots and word frequency distributions to illustrate the effectiveness of the methods.

### Results
The project demonstrates the strengths and limitations of each summarization approach, providing insights into their applicability for summarizing Tamil text. The evaluation results highlight the performance of both extractive and abstractive methods.

## Getting Started

### Prerequisites
- Python 3.8 or above
- Required libraries listed in `requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/extractive-abstractive-summarization.git
2. Navigate to the project directory:
   ```bash
   cd extractive-abstractive-summarization
