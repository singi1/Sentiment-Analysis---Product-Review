
## 📌 Task: Structuring Customer Reviews with Generative AI  

### 🔍 Overview  
Sentiment analysis helps businesses understand customer opinions by categorizing feedback as positive, negative, or neutral. In this task, you'll develop an AI-powered approach to structure unstructured customer reviews, making them actionable for product improvements.  

### 🎯 Goal  
As a product analyst at a multinational tech company (computers, phones, laptops, and hardware), your objective is to design an **effective prompt** for a Generative AI model. This prompt should:  
- Accept raw customer reviews as input.  
- Generate structured outputs that can be used to enhance customer experience.  

### 🛠️ What You Need to Do  
1. **Design a Prompt:** Craft a clear and efficient prompt for AI to extract structured data from customer reviews.  
2. **Extract Key Insights:** Ensure the output captures the following:  
   - **Date of the review**  
   - **Product/service mentioned**  
   - **Rating (if available)**  
   - **Short summary (≤100 words) of the feedback**  
   - **List of actionable improvement points**  
   - **Competitor mentions (if applicable) & what was better**  
   - **Overall sentiment (Positive, Negative, or Neutral)**  
3. **Optimize for Usability:** Ensure the structured response is clear, concise, and useful for decision-making.  

### 📂 Expected Output Format  
Your AI prompt should produce an output like this:  

```json
{
  "date": "2025-03-28",
  "product": "XYZ Laptop",
  "rating": 3.5,
  "summary": "The battery life is shorter than expected, but the display quality is great.",
  "action_items": [
    "Improve battery optimization",
    "Enhance customer support response time"
  ],
  "competitor_comparison": {
    "competitor_name": "ABC Laptops",
    "better_aspect": "Longer battery life"
  },
  "sentiment": "Neutral"
}
```  

### 🚀 Next Steps  
- Implement and test your AI prompt using a Generative AI model (e.g., ChatGPT, Gemini, or Claude).  
- Share your prompt and example outputs in the repository.  
- Discuss improvements based on test results and feedback.  

---  

Would you like any modifications to this format before you publish it?
