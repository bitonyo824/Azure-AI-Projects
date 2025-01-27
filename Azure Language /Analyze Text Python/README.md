
# Text Analysis using Azure Language Services

## Description
This project is part of the Microsoft AI MS Learn series. It uses Azure Language Services to perform text analysis. The script processes text to detect language, analyze sentiment, extract key phrases, and identify entities and linked entities. 

## Objectives
- Demonstrate integration with Azure Language Services for real-world text analysis.
- Implement a solution architecture leveraging Azure's AI capabilities for language detection, sentiment analysis, and entity recognition.
- Showcase problem-solving skills in cloud-based AI and machine learning.

## Technologies Used
- Azure AI Text Analytics for language detection, sentiment analysis, key phrase extraction, and entity recognition.
- Python for scripting and automation.
- Azure SDKs and APIs.

## Setup and Installation
To set up this project:
```
git clone https://github.com/b8234/Azure-AI-Projects.git
cd Azure-AI-Projects/Azure\ Language/Analyze\ Text\ Python/text-analysis
```

**Install Dependencies**:

```bash
pip3 install python-dotenv azure-ai-textanalytics azure-core
```
Or install the required dependencies via requirements, run the following command:

```bash
pip3 install -r requirements.txt
```

## Configuration
- Set up an Azure Cognitive Services resource in the Azure portal, choosing either the Azure AI services multi-service option or the     single language resource.
- Create a `.env` file with Azure service credentials:
  ```
  COG_SERVICE_KEY=your_key
  COG_SERVICE_ENDPOINT=your_endpoint
  ```

## How to Use
Run the script with:
```
python3 text-analysis.py
```

## Architectural Insights
- The project is designed to efficiently process text data using Azure AI, ensuring scalability and security, key concerns in cloud architecture.
- The script design allows for easy adaptation and integration into larger cloud solutions.

## Example Output
- Example output is in the Output folder

## Learning Outcomes
- Gained a deeper understanding of Azure AI services and their application in text analytics.
- Developed skills in creating cloud-based AI solutions that are scalable and secure.

## Acknowledgments
This project is inspired by exercises in the [Microsoft AI MS Learn series](https://learn.microsoft.com/en-us/training/).

## Contact

If you have any questions or feedback, feel free to [open an issue](https://github.com/b8234/Azure-AI-Projects/issues/new). I welcome your input and suggestions to improve this repository further.


