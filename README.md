# NMT-System-HuggingFace
Neural Machine Translation (NMT) System



### **Project Title: Neural Machine Translation (NMT) System**

#### **Purpose & What it Does:**

This website provides an interactive Neural Machine Translation (NMT) system, allowing you to translate text between different languages. It's designed to showcase and compare the capabilities of two distinct state-of-the-art machine translation models: **MarianMT** and **NLLB-200**.

Our goal is to offer a flexible translation tool while demonstrating the trade-offs and strengths of specialized vs. multilingual models.

#### **How to Use It:**

1.  **Enter Your Text:** Type or paste the text you wish to translate into the "Input Text" box.
2.  **Select Languages:** Choose your "Source Language" (the language of your input text) and your desired "Target Language" (the language you want to translate to) using the dropdown menus.
3.  **Choose a Model:**
    *   **MarianMT (en-fr):** Select this model for highly optimized, fast, and accurate translations specifically from **English to French**. It's a great choice if you only need this particular language pair.
    *   **NLLB-200:** Choose this powerful model for translating between a wide array of languages. It offers **extensive multilingual support**, allowing you to translate between English, French, Hindi, and potentially many more languages (depending on the implementation). Be aware that it might be slightly more resource-intensive.
4.  **Adjust Parameters (Optional):** Fine-tune translation behavior using advanced parameters like `Max Length`, `Num Beams`, `Length Penalty`, `Temperature`, `Top K`, and `Top P` to experiment with different translation styles.
5.  **Get Your Translation:** Click the "Translate" button (or similar, depending on your Gradio interface design) to see the translated output.

#### **Key Features:**

*   **Dual Model Comparison:** Directly compare translations from a specialized English-French model (MarianMT) and a broadly multilingual model (NLLB-200).
*   **Configurable Parameters:** Experiment with various decoding strategies to understand their impact on translation quality.
*   **Performance Insights:** (If you include a section for it) Observe metrics like translation speed and memory usage for each model.
