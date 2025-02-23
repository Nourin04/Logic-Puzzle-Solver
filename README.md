# 🧩 **Logic Puzzle Solver**  

A web-based application that uses Optical Character Recognition (OCR) and AI to analyze, interpret, and solve logic or math puzzles from uploaded images. The solution includes step-by-step reasoning and the final answer. This project integrates the **DeepSeek LLaMA-70B** model via GROQ for advanced reasoning and puzzle-solving capabilities.

---

## 🚀 **Features**
- 🔍 **Text Extraction**: Uses EasyOCR to extract text from uploaded images.
- 🧠 **AI Reasoning with DeepSeek**: Solves puzzles using the **DeepSeek LLaMA-70B** model through the GROQ API for accurate and detailed explanations.
- 📷 **Image Upload Support**: Supports drag-and-drop, file upload, or direct camera capture.
- 📄 **Step-by-Step Solutions**: Provides detailed explanations of each step to reach the answer.
- 🎨 **User-Friendly Interface**: Clean, responsive UI built with Gradio.

---

## 🔧 **Tech Stack**
- **Gradio**: For building an interactive and user-friendly web interface.
- **EasyOCR**: For text recognition from images.
- **GROQ API**: Uses **DeepSeek LLaMA-70B** model for AI-based puzzle-solving.
- **Torch**: Backend support for OCR and model integration.
- **Pillow**: Image processing library for saving and handling images.

---

## 🛠️ **Usage**

### 🔑 **Set Your GROQ API Key**
Replace the placeholder key with your actual GROQ API key:
```python
GROQ_API_KEY = "your_groq_api_key_here"
```

### ▶️ **Run the App**
Run the Python script:
```bash
python app.py
```


## 📋 **How It Works**

1. **Upload Image**  
   Upload an image containing the logic puzzle or math equation.

2. **OCR Extraction**  
   The app uses `EasyOCR` to extract text from the uploaded image.

3. **AI Solving (DeepSeek Model)**  
   Sends the extracted text to the **DeepSeek LLaMA-70B** model via GROQ to identify patterns, solve the puzzle, and return a step-by-step solution.

4. **Solution Display**  
   The app displays the formatted solution, including:
   - **Given Equation**
   - **Identified Pattern**
   - **Step-by-Step Calculations**
   - **Final Answer**

---



## ❓ **FAQ**

**Q:** What types of puzzles can it solve?  
**A:** The app works best with simple logic puzzles, mathematical equations, and pattern-based puzzles.

**Q:** Why use the DeepSeek LLaMA-70B model?  
**A:** This model offers advanced reasoning capabilities, delivering more accurate and context-aware solutions for complex puzzles.

**Q:** Does it require an internet connection?  
**A:** Yes, for API calls to the GROQ model.

---

## 📜 **License**
This project is licensed under the [MIT License](LICENSE).

---

## 🙏 **Acknowledgments**
- [Gradio](https://gradio.app/)
- [EasyOCR](https://github.com/JaidedAI/EasyOCR)
- [GROQ](https://groq.com/)
- [DeepSeek LLaMA-70B](https://huggingface.co/deepseek-ai)
- [PyTorch](https://pytorch.org/) 

