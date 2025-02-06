# Run Any Ollama Model on Google Colab with Custom UI! 🚀

This repository provides a simple and free way to run any Ollama language model on Google Colab and connect it to a user-friendly interface. No more resource limitations! 🎉

## Features ✨

* **Free GPU Access:** Leverage Google Colab's free GPUs to run large Ollama models. 🎁
* **Easy Setup:** Step-by-step instructions in the Colab notebook.  ➡️
* **Customizable UI:** Connect your Ollama model to a Hugging Face Space for a streamlined chat experience. 💬
* **Run any Ollama Model:** Adaptable for different model sizes and types.  ⚙️


## Getting Started 🚦

1. **ngrok Authtoken:** Obtain an authtoken from [ngrok](https://ngrok.com/). You'll need a free account. This is crucial for exposing your Colab runtime. 🔑
2. **Google Colab:** Open the provided Colab notebook: [Link](https://colab.research.google.com/drive/1BJbUnfZ0qoouDyafjsWcth5JHhITSL78#scrollTo=EhKXNqknGilz) 💻
   * Add you Auth Token in the Secrets Tab  
   * Connect to the T4 Runtime Type. 
   * Run both the cells. 
   * On sucessfully connection of ollama with ngrok you'll get a ngrok link, copy it. 
3. **Duplicate the Huggingface Spaces:** 
    [![Duplicate Space](https://img.shields.io/badge/Duplicate%20Space-Hugging%20Face-blue?logo=huggingface)](https://huggingface.co/spaces/chandrakant-s4/open-webui?duplicate=true)
   * Wait for sometime till it is installing necessary libraries. 🛠️
   * Create your admin account. 🔒
   * Navigate to the Settings > Admin Settings.  ⬇️
   * Head over to the Connections > Disable Open API toggle > Enable Ollama API toggle button.  ⬇️
   * Now change the Ollama url to the ngrok url you got on Colab ⬇️
   * Make sure to remove the last forward slash in the url. ⬇️
   * Click Save.  🔗
   * Click Strat new Chat.  🔗
   * Now you would be able to see all the models in the select model drop down! :)  🔗
   * Happpily Prompt Now!  🔗


## Troubleshooting ⚠️

* **ngrok Issues:** Make sure your authtoken is correctly set. Check the ngrok dashboard for any errors.  🕵️‍♀️


## Contributing 🙌

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.


## License ⚖️

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
