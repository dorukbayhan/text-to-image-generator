# text-to-image-generator
								                                                  INFINIA AI Image Generator
Project Overview
	The INFINIA AI Image Generator uses OpenAI's GPT-3.5 model to enhance text inputs and generate images based on those enhanced descriptions using Hugging Face's Stable Diffusion model. 
	The system aims to create imaginative images based on descriptions provided by the user.

  Technologies Used
		OpenAI GPT-3.5 API: Used for text enhancement. Short descriptions entered by the user are expanded into detailed futuristic descriptions by GPT-3.5.

		Hugging Face Diffusers (Stable Diffusion): The enhanced text is passed to the Stable Diffusion model to generate an image.

		IPyWidgets: Provides a user-friendly interface within the Colab environment, allowing for easy tracking of the image generation process.

		Google Colab: Used to run the model and provide GPU access for image generation.

     Setup and Requirements
	I recommend using Google Colab to run this project. Follow the steps below to set up and run the project.

Step 1: Go to Google Colab
		Navigate to the provided Google Colab link.
		https://colab.research.google.com/

Step 2: Run the Code
  Follow these steps:

Get API Key:

Obtain an API key from OpenAI.


Start the Notebook:
	Insert the OpenAI key in the provided fields.

	Open the ipynb file from this repository and run it in Google Colab.

Step 3: Required Libraries
The following libraries are required for the project:

- requests
- json (Getting Enhance text from external source with json API)
- torch
- diffusers (Hugging Face Library)
- PIL (Pillow)
- IPython
- ipywidgets (for UI)

These libraries will be automatically installed in the Colab environment.
When you first start the code there will be a installation process for Hugging Face's Stable Diffusion model

Step 4: Generate an Image
	Enter a Prompt: Provide a description (e.g., "a futuristic city with flying cars").

	Enhance Text: The system will use the GPT-3.5 model to enhance the entered description.

	Generate Image: The enhanced description will be passed to the Stable Diffusion model to create an image.(Pipeline created)

	View Image: The generated image will be displayed within the Colab interface.

Usage Steps
        	Open Colab and Run the Code: Execute the code step-by-step to start the project.

		Enter API Keys: Insert your OpenAI and Hugging Face API keys in the appropriate fields.

		Input the Prompt: Type your description into the input box on the screen.

		Generate Image: The system will enhance your description and generate the corresponding image.

		View and Download Image: The generated image will appear on the screen.

UI Features
Input Box: A text box to enter the description.

Image Display: The generated image will be displayed on the screen.

Progress Bar: A progress bar will show the status of the image generation process.

Project Architecture
Prompt Input: A short description is taken from the user.

Text Enhancement: The description is enhanced using OpenAI GPT-3.5.

Image Generation: The enhanced text is passed to Hugging Face Stable Diffusion to generate an image.

UI: A user-friendly interface tracks the image generation process.
