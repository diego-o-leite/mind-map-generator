# 📚📄Mind Map Generator💭🗺️

<span style="display: flex; align-items: center;">
  <img src="https://img.shields.io/badge/COUNTRY-gray?style=for-the-badge&labelColor=gray&logoWidth=0" alt="Country Badge" style="margin: 0; padding: 0; border: none;" />
  <img src="https://flagpedia.net/data/flags/h80/br.png" alt="Brazil Flag" height="28" style="margin: 0; padding: 0; border: none;" />
</span><br>

![GitHub repo size](https://img.shields.io/github/repo-size/diego-o-leite/mind-map-generator?style=for-the-badge) 


![](https://raw.githubusercontent.com/diego-o-leite/assets/main/mind-map-generator/img/cover_image.png)


The Mind Map Generator enables batch conversion of PDF files into mind maps.

Your PDFs are first converted into .puml files using Jupyter Notebook and Google's Generative AI (Gemini-1.5-Flash). Then, the .puml files are rendered into .png images using PlantUML.

## 🏛️Architecture overview📐

![](https://raw.githubusercontent.com/diego-o-leite/assets/main/mind-map-generator/img/architecture%20overview.png)

## 🔧Installation🪛

1. **Clone the repository:**
   
   - `git clone https://github.com/your-username/mind-map-generator.git`

   - `cd mind-map-generator`

1. 1. **Install the dependencies:**
   
   Run the following command to install all necessary packages:

      - `pip install google-generativeai python-dotenv IPython tenacity ipywidgets`

   This command installs:
   - `google-generativeai`: For interacting with Google's generative AI models
   - `python-dotenv`: For loading environment variables
   - `IPython`: For enhanced interactive Python experiences
   - `tenacity`: For implementing retry logic
   - `ipywidgets`: For creating interactive widgets in Jupyter notebooks

1. **Configure the API key:**
   1. [Check here how you can create a key with a few clicks in Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key)
   1. Follow the instructions in the [`example_keys.env`](example_keys.env) file to set up your API key securely.

1. **Install Jupyter:**
    - [Check here how you can install Jupyter](https://jupyter.org/install)

1. **Ensure Java is installed.**


## 📖Quick Usage Guide⚡

🔗 <strong><a href="https://diego-o-leite.github.io/assets/mind-map-generator/docs/usage_guide.pdf"  rel="noopener noreferrer">Access the Quick Usage Guide (PDF)</a></strong>

📌 This guide includes:
- Overview
- Security configuration
- The ‘inputs’ folder
- Mind maps generation
- The ‘outputs’ folder
- Manual adjustment


## 💡Ideas for Future Implementation🔮

1. Accept other types of text documents like .txt and .docx as inputs.
1. Divide inputs into smaller parts to create more comprehensive mind maps.
1. Offer the user options for adjustments in the prompt (e.g., requesting the mind map in another language).
1. Offer a more user-friendly interface to execute  commands.
1. Provide Mermaid file export option for mind maps, enabling import into tools like Excalidraw.

## 🚧Cautions and Tips⚠️

1. Large PDFs (e.g., over 20 pages) can make it challenging for the A.I. to provide a more satisfactory response. If this occurs:
   1. Attempt to create an initial map with the entire PDF to get an overview.
   1. If the initial attempt is unsuccessful or too slow, divide the PDF into smaller sections (e.g., 20 pages each) and generate separate mind maps for each part using the Mind Map Generator.
   1. Use a PDF editor to divide the document.


## ❗Contribution🤝

At the moment, we may not be able to dedicate time to external contributions.

## 🤗Support and Community🧩

[GitHub issues](https://github.com/diego-o-leite/mind-map-generator/issues/)

## License

This project is licensed under the GNU General Public License v3.0.

See the [LICENSE](LICENSE) file for more details.