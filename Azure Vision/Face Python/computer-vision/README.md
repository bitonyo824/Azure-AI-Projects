# Azure Computer Vision Image Tagging Projects

## Description
These projects are a part of the Microsoft AI MS Learn series. They use Azure Cognitive Services Computer Vision. The first script tags elements in a local image, while the second script performs similar tagging on a remote image. These projects demonstrate the application of Azure AI in analyzing and categorizing visual content from different sources.

## Objectives
- Implement Azure Cognitive Services Computer Vision for both local and remote image analysis.
- Utilize the Computer Vision API to identify and categorize elements within images.
- Showcase the versatility of Azure AI in interpreting visual data from various sources.

## Technologies Used
- Azure Cognitive Services Computer Vision for image analysis.
- Python for scripting and Azure service integration.
- PIL (Python Imaging Library) for handling local image files.

## Setup and Installation
To set up and run these projects:

```
git clone https://github.com/b8234/Azure-AI-Projects.git
cd Azure-AI-Projects/Azure\ Vision/Face\ Python/computer-vision
```

Run command to install packages:

```
pip3 install azure-cognitiveservices-vision-computervision Pillow
```

Or install the required dependencies via requirements, run the following command:

```bash
pip3 install -r requirements.txt
```

## Configuration

### Provision an Azure AI Services Resource

If you don’t already have one in your subscription, you’ll need to provision an Azure AI Services resource. Follow these steps:

1. Open the Azure portal at [https://portal.azure.com](https://portal.azure.com) and sign in using the Microsoft account associated with your Azure subscription.
2. In the top search bar, search for "Azure AI services" and select Azure AI Services.
3. Create an Azure AI services multi-service account resource with the following settings:
   - Subscription: Your Azure subscription.
   - Resource group: Choose or create a resource group. (If you are using a restricted subscription, you may not have permission to create a new resource group - use the one provided).
   - Region: Choose any available region.
   - Name: Enter a unique name.
   - Pricing tier: Standard S0.
   - Select the required checkboxes and create the resource.
4. Wait for deployment to complete, and then view the deployment details.
5. When the resource has been deployed, go to it and view its Keys and Endpoint page. 

### Create an .env file to store credentials

- Create a `.env` file with your Azure service credentials:
  ```
  VISION_KEY=your_vision_key
  VISION_ENDPOINT=your_vision_endpoint
  ```

## How to Use
- For local image tagging, run the first script with a local image file.
- For remote image tagging, run the second script which accesses an image via a URL.

```
python3 detect-people_file.py
```
```
python3 detect-people_url.py
```

## Example Output
Example output is in the Example Output folder.

## Learning Outcomes
- Gained experience in using Azure AI services for analyzing both local and remote images.
- Developed skills in creating Python applications that leverage Azure Cognitive Services for computer vision tasks.
- Enhanced understanding of the practical applications of AI in image processing and analysis.

## Acknowledgments
These projects were inspired by exercises in the [Microsoft AI MS Learn series](https://learn.microsoft.com/en-us/training/)


## Contact

If you have any questions or feedback, feel free to [open an issue](https://github.com/b8234/Azure-AI-Projects/issues/new). I welcome your input and suggestions to improve this repository further.

