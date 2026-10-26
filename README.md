<<<<<<< HEAD
# 🤖 AI Token & Cost Calculator + Prompt Compressor

A web-based developer utility that estimates AI prompt token usage, compares API costs across multiple AI models, and compresses prompts to reduce unnecessary text.

## 🚀 Features

- **Prompt Statistics:** Count characters, words, and estimated tokens.
- **Prompt Compression:** Remove unnecessary filler words and redundant phrases using predefined replacement rules.
- **Token Savings:** Compare estimated token usage before and after compression.
- **AI API Cost Comparison:** Compare estimated input-token costs across OpenAI, Anthropic Claude, and DeepSeek models.
- **Production Scale Simulator:** Estimate costs for 1, 100, 1,000, 10,000, or 100,000 API calls.
- **Copy Optimized Prompt:** Copy the compressed prompt to your clipboard.
- **Responsive UI:** A modern, dark-themed interface built with Tailwind CSS.
- **Sample Prompt:** Load a sample prompt to test the compressor.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Tailwind CSS

## 📸 How to Use

1. Open the application in your browser.
2. Paste your prompt into the **Original Prompt** field.
3. Review the character, word, and estimated token counts.
4. Click **Compress Prompt** to optimize the text.
5. Compare the original and compressed prompts.
6. Select the number of API calls to estimate costs at different scales.
7. Compare estimated costs across the listed AI models.
8. Copy the optimized prompt or apply it to the calculator again.

## 💰 Supported AI Models

The current pricing table includes:

- GPT-4o
- GPT-4o-mini
- o1
- Claude 3.5 Sonnet
- Claude 3.5 Haiku
- DeepSeek-V3
- DeepSeek-R1

**Note:** Model names and prices are defined in the source code and may become outdated. Verify current provider pricing before making real budgeting decisions.

## ⚙️ Installation and Setup

No build tools or package installation are required.

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project folder.
3. Open `index.html` in your web browser.

Alternatively, download the repository and open `index.html` directly.

## 📂 Project Structure

```text
ai-token-cost-calculator/
├── index.html
└── README.md
```

## ⚠️ Important Notes

- Token counts are estimates, not exact tokenizer results.
- Prompt compression uses predefined text-replacement rules; it does not use an AI model.
- Compression may change wording or meaning in some prompts. Review the output before using it.
- Cost calculations use the pricing values stored in the source code.
- The calculator estimates input-token costs only. It does not make live API calls or include output-token charges.
- Tailwind CSS is loaded from a CDN, so an internet connection is required for its styling.

## 🔮 Future Improvements

- Add editable model pricing.
- Integrate accurate tokenizers for supported models.
- Support input and output token pricing separately.
- Add more AI providers and models.
- Improve prompt compression while preserving meaning.
- Add automated tests for token estimation and cost calculations.

## 👨‍💻 Author

**Nouman Lodhi**

💡 **Idea & Project Concept:** Nouman Lodhi  
🤖 **Development:** Built with AI assistance  
🛠️ **Technologies:** HTML, CSS, JavaScript, Tailwind CSS

This project started as my own idea to create a tool that estimates AI token usage, compares API costs, and helps optimize prompts. I used AI assistance during development as a learning opportunity while exploring web development and AI tools.

**My goal:** Keep learning, improve my coding skills, and turn my ideas into useful software projects.

## 📄 License

This project is available for learning and personal development. Add a license file if you want to specify the permissions and conditions for reuse.
=======
# ai-token-cost-calculator
An AI Token &amp; Cost Calculator with Prompt Compressor 💡 | Original idea by Nouman Lodhi, developed with AI assistance using HTML, CSS, and JavaScript.
>>>>>>> 7894bc9fd7f86a0b737aa957ff42377caccb2552
