# **Run Any Ollama Model on Google Colab with a Custom UI! 🚀**  

This repository provides a **simple, free, and efficient** way to run any **Ollama language model** on **Google Colab** and connect it to a **user-friendly interface**. Say goodbye to resource limitations! 🎉  


## **Features ✨**  

✅ **Free GPU Access** – Utilize Google Colab’s free GPUs to run large Ollama models effortlessly.  
✅ **Easy Setup** – Step-by-step instructions provided in the Colab notebook.  
✅ **Customizable UI** – Connect your Ollama model to a **Hugging Face Space** for an intuitive chat experience.  
✅ **Supports Any Ollama Model** – Easily adaptable for different model sizes and types.  


## **Getting Started 🚦**  

### **1️⃣ Obtain an ngrok Authtoken**  
- Create a free account on **[ngrok](https://ngrok.com/)**.  
- Retrieve your **authtoken**, which is essential for exposing your Colab runtime.  

### **2️⃣ Set Up Google Colab**  
- Open the provided **Google Colab Notebook**: [📌 Click Here](https://colab.research.google.com/drive/1BJbUnfZ0qoouDyafjsWcth5JHhITSL78#scrollTo=EhKXNqknGilz)  
- Add your **ngrok Authtoken** in the **Secrets Tab**.
- ![](screenshots/1%20_%20secrets.png)
- Connect to the **T4 GPU runtime type**.  
- Run both the cells.  
- Once **Ollama is successfully connected to ngrok**, you will receive an **ngrok URL** – **Copy it!** 🔗  
  ![](screenshots/2%20_%20ngrok_url.png)
  ![](screenshots/3%20_%20ollama%20running.png)

### **3️⃣ Deploy to Hugging Face Spaces**  
- Duplicate the Hugging Face Space using the button below:  

  [![Duplicate Space](https://img.shields.io/badge/Duplicate%20Space-Hugging%20Face-blue?logo=huggingface)](https://huggingface.co/spaces/chandrakant-s4/open-webui?duplicate=true)  

- Wait for the **installation of necessary libraries**. 🛠️  
- **Create an Admin account**. 🔒
- ![](screenshots/4%20_%20UI%20settings.png)
- Navigate to **Settings > Admin Settings**.  
- Go to **Connections**:  
  - Disable the **Open API** toggle.  
  - Enable the **Ollama API** toggle.  
- Change the **Ollama URL** to the **ngrok URL** you copied from Colab.  
- **Remove the trailing forward slash ("/")** in the URL.
- ![](screenshots/5%20_%20Connections.jpg)
- Click **Save**.  
- Click **Start New Chat**.
- ![](screenshots/6%20_%20New%20Chat.jpg)
- You should now see all available **Ollama models** in the dropdown! 🎉  


## **Troubleshooting ⚠️**  

🔹 **ngrok Issues** – Ensure your **authtoken** is correctly set. If you face issues, check your **ngrok dashboard** for any errors.  


## **Contributing 🙌**  

Contributions are **highly encouraged**! If you find any **bugs** or have **suggestions** for improvement, feel free to **open an issue** or submit a **pull request**.  


## **License ⚖️**  

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
