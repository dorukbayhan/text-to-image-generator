# INFINIA AI Image Generator

##  Project Overview
The **AI Image Generator** uses **OpenAI's GPT-3.5 model** to enhance text inputs and generate images based on those enhanced descriptions using Hugging Face's **Stable Diffusion** model.  
The system aims to create imaginative images based on descriptions provided by the user.

---

##  Technologies Used

- **OpenAI GPT-3.5 API**  
  Used for text enhancement. Short descriptions entered by the user are expanded into detailed futuristic descriptions by GPT-3.5.

- **Hugging Face Diffusers (Stable Diffusion)**  
  The enhanced text is passed to the Stable Diffusion model to generate an image.

- **IPyWidgets**  
  Provides a user-friendly interface within the Colab environment, allowing for easy tracking of the image generation process.

- **Google Colab**  
  Used to run the model and provide GPU access for image generation.

---

##  Setup and Requirements

I recommend using **Google Colab** to run this project. Follow the steps below to set up and run the project.

### Step 1: Go to Google Colab

Navigate to the provided Google Colab link:  
[https://colab.research.google.com/](https://colab.research.google.com/)

### Step 2: Run the Code

1. **Get API Key**  
   - Obtain an API key from OpenAI.

2. **Start the Notebook**  
   - Insert the OpenAI key in the provided field.  
   - Open the `main.ipynb` file from this repository and run it in Google Colab.

### Step 3: Required Libraries

The following libraries are required for the project:

- `requests`
- `json` (for getting enhanced text from external API)
- `torch`
- `diffusers` (Hugging Face Library)
- `PIL` (Pillow)
- `IPython`
- `ipywidgets` (for UI)

>  These libraries will be automatically installed in the Colab environment.  
> When you first start the code, there will be an installation process for Hugging Face's Stable Diffusion model.

### Step 4: Generate an Image

- **Enter a Prompt**: Provide a description (e.g., `"a futuristic city with flying cars"`).
- **Enhance Text**: The system will use GPT-3.5 to enhance the description.
- **Generate Image**: The enhanced description will be passed to Stable Diffusion.
- **View Image**: The generated image will be displayed within the Colab interface.

---

##  Usage Steps

1. Open Colab and run the code step-by-step.
2. Enter your **OpenAI API key**.
3. Input your **description** in the prompt box.
4. Click **Generate Image**.
5. View and optionally **download the image**.

---

##  UI Features

- **Input Box**: A text box to enter the description.
- **Image Display**: The generated image is displayed on the screen.
- **Progress Bar**: Shows the current status of the image generation process.

---

##  Project Architecture

1. **Prompt Input**: A short description is taken from the user.
2. **Text Enhancement**: The description is enhanced using OpenAI GPT-3.5.
3. **Image Generation**: The enhanced text is passed to Hugging Face Stable Diffusion.
4. **UI**: A user-friendly interface tracks the process and displays results.

---

