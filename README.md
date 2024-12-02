# Mind Map Generator

![GitHub repo size](https://img.shields.io/github/repo-size/diego-o-leite/assets?style=for-the-badge)

<img src="img/cover_image.png" alt="What does this project do?">


The Mind Map Generator allows you to automatically convert PDF files into mind maps in batches using Google's Generative AI (Gemini).

## Architecture overview

<img src="img/architecture overview.png" alt="Exemplo imagem">

## 🔧 Installation 🪛

1. **Clone the repository:**
   
   - `git clone https://github.com/your-username/mind-map-generator.git`

   - `cd mind-map-generator`

1. **Install the dependencies:**
   
   - `pip install google-generativeai python-dotenv IPython`

1. **Configure the API key:**
   1. [Check here how you can create a key with a few clicks in Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key#windows)
   1. Follow the instructions in the [`example_keys.env`](example_keys.env) file to set up your API key securely.

1. **Install Jupyter:**
    - [Check here how you can install Jupyter](https://jupyter.org/install)

1. **Ensure Java is installed.**

## 🎬 Usage 🪄

1. Place your PDF files in the folder 'inputs' of the repository 'mind-map-generator':
![](https://raw.githubusercontent.com/diego-o-leite/assets/main/mind-map-generator/gifs/placing_pdfs_in_folder_inputs.gif)
1. Run the Jupyter Notebook script to convert the PDFs into mind maps.

1. The generated mind maps will be saved in the output folder.

## 🤝 Contribution 

Currently, we are not able to work on external contributions.

## 🧑‍🤝‍🧑 Support and Community

[GitHub issues](https://github.com/diego-o-leite/assets/issues/)

## License

This project is licensed under the GNU General Public License v3.0.

See the [LICENSE](LICENSE) file for more details.