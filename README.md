# Image-Generation-with-OpenAI-s-DALL-E-3-via-Azure-API

# Image Generation with OpenAI's DALL-E 3 via Azure API

This project demonstrates how to generate images using OpenAI's DALL-E 3 model through the Azure OpenAI API. The script initializes the Azure OpenAI client, sends a request to generate an image based on a textual prompt, and retrieves the generated image's URL.

## Prerequisites

Before running this script, ensure you have the following:

- An Azure OpenAI subscription.
- The `openai` Python package installed.
  - You can install it using pip:

    ```bash
    pip install openai
    ```

- Your Azure OpenAI API endpoint and API key.

## Configuration

1. Replace the `azure_endpoint` with your Azure OpenAI endpoint.
2. Replace the `api_key` with your Azure OpenAI API key.

## Script Explanation

1. **Initialize Azure OpenAI Client**: The `AzureOpenAI` client is initialized using the provided endpoint and API key.
2. **Generate Image**: Using the `client.images.generate` method, an image is generated with the specified prompt (`"A person riding royal enfield in rain"` in this case).
3. **Extract Image URL**: After generating the image, the script extracts the URL of the generated image from the API response.
4. **Display Image URL**: The script prints the URL of the generated image, which can be used to view or download the image.
