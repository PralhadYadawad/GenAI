# GenAI
AI-Powered Tweet Generation: Leveraging  GPT-2 for Contextual and Mood-Based  Tweet Creation
### README for GitHub: **Generative AI-based Tweet Generation System**

---

# **Generative AI-based Tweet Generation System**

This project leverages **Generative AI models** (e.g., GPT-2) to automatically generate contextually relevant, concise, and engaging tweets. It is designed to simplify social media content creation by automating tweet generation while preserving creativity and relevance.

---

## **Features**
- **Contextual Tweet Generation**: Generates tweets based on user-defined topics and optional moods.  
- **Customization**: Allows users to define the tone or sentiment of the generated tweets.  
- **Character Limit Adherence**: Ensures all tweets remain within Twitter's 280-character limit.  
- **AI-Powered**: Uses **GPT-2**, a transformer-based model, for high-quality text generation.  

---

## **How It Works**
1. **Input**: Users provide a topic and optionally a mood (e.g., cheerful, professional).  
2. **Processing**: The model generates a tweet using the given inputs.  
3. **Output**: A concise, contextually relevant tweet is displayed.

---

## **Technologies Used**
- **Python**
- **Transformers Library (Hugging Face)**
- **Torch (PyTorch)**  
- **GPT-2 Medium Model**  

---

## **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/pralhadyadawad/GenAI.git
   ```
2. Install dependencies:
   ```bash
   pip install transformers torch
   ```
3. Run the script:
   ```bash
   python Tweet_Generation.py
   ```
4. Enter a topic and an optional mood when prompted to generate a tweet.

---

## **Code Overview**
- **`generate_tweet` function**: Core function to generate tweets based on user inputs.  
- **Model and Tokenizer**: GPT-2 medium model and tokenizer from the Hugging Face Transformers library are used.  
- **Settings**: Parameters like `max_length`, `top_k`, and `top_p` control the quality and diversity of generated tweets.  

---

## **Example Usage**
```bash
Enter the topic: AI in healthcare
Enter the mood (optional): inspiring

Generated Tweet:
"AI is revolutionizing healthcare by enabling faster diagnoses and better patient outcomes. The future of medicine is here!"  
```

---

## **Future Enhancements**
- Add fine-tuning capabilities for domain-specific tweets.  
- Integrate with the Twitter API for direct posting of generated tweets.  
- Enhance customization for tone, sentiment, and style.  

---

## **Contributions**
Contributions are welcome! Feel free to open issues or submit pull requests to improve the system.

---

**Authors:**  
Pralhad R Yadawad and Pradeep Laxmanrao Pawar

