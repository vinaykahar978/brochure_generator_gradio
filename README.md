# 📄 Brochure Generator (Gradio)

A lightweight AI application that **scrapes any company website** and instantly generates a **professional brochure** using **OpenAI** or **Gemini**.
Built with **Gradio**, deployed on **Hugging Face Spaces**, and fully open-source on GitHub.

---

## 🚀 Live Demo

Try the app here:
👉 **[https://huggingface.co/spaces/vinaykahar978/brochure_generator_gradio](https://huggingface.co/spaces/vinaykahar978/brochure_generator_gradio)**

---

## 📦 Repository

GitHub source code:
👉 **[https://github.com/vinaykahar978/brochure_generator_gradio](https://github.com/vinaykahar978/brochure_generator_gradio)**

---

## 🧩 Features

* Generate a clean, short brochure from any landing page.
* Uses BeautifulSoup to fetch and extract webpage text.
* Choose between **GPT** (OpenAI) or **Gemini** (Google).
* Live streaming responses for a smoother user experience.
* Simple and user-friendly Gradio interface.

---

## 🛠️ Tech Stack

* **Python**
* **Gradio**
* **OpenAI API**
* **Google Gemini API**
* **BeautifulSoup (bs4)**
* **Requests**

---

## 📁 Project Structure

```
.
├── app.py               # Main application script
├── requirements.txt     # Python dependencies
├── runtime.txt          # Python version for Hugging Face
└── README.md            # Project documentation
```

---

## ⚙️ Installation (Local Development)

### 1️⃣ Clone the repo

```bash
git clone https://github.com/vinaykahar978/brochure_generator_gradio.git
cd brochure_generator_gradio
```

### 2️⃣ Install requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Add your API keys

Create a `.env` file in the project root:

```
OPENAI_API_KEY=your-key-here
GOOGLE_API_KEY=your-key-here
```

### 4️⃣ Run the app

```bash
python app.py
```

Then open:
👉 [http://localhost:7860](http://localhost:7860)

---

## 🌐 Deploying to Hugging Face Spaces

The project is already deployed here:
**[https://huggingface.co/spaces/vinaykahar978/brochure_generator_gradio](https://huggingface.co/spaces/vinaykahar978/brochure_generator_gradio)**

To deploy your own:

1. Create a new **Gradio Space**
2. Upload project files or push via Git
3. Add Secrets:

   * `OPENAI_API_KEY`
   * `GOOGLE_API_KEY`
4. Hugging Face builds automatically

---

## 🔒 Security Notes

* **Never commit API keys** or `.env`.
* Always use Hugging Face **Secrets** when deploying.

