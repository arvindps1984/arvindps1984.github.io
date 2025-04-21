AI-Powered Recipe Retrieval System: A Kaggle Capstone Project

🍳 Introduction
In today’s fast-paced world, finding the perfect recipe can be overwhelming. With countless cuisines, ingredients, and cooking times to consider, an AI-powered solution can simplify the search.
This [Kaggle notebook] (https://www.kaggle.com/code/arvindshankar/ai-recipe-retrieval-system-2025-q1-capstone/notebook?scriptVersionId=235125966) demonstrates how Google’s Gemini AI can intelligently retrieve recipes from a structured dataset, making culinary exploration effortless.

🔍 Problem Statement
Given a Kaggle recipe dataset, how can we: 

✔ Quickly find recipes by cuisine, cooking time, or ingredients? 
✔ Allow natural language queries (e.g., "Find me a 30-minute Italian dish")? 
✔ Automate filtering without manual DataFrame operations?

Traditional methods require exact column filters, but AI-driven retrieval makes it conversational.

💡 The Solution: AI-Powered Recipe Search
This project leverages Gemini’s function-calling to: 

   ✅ Convert natural language queries into structured database operations. 
   ✅ Dynamically filter recipes using Pandas DataFrame queries. 
   ✅ Provide instant, formatted responses.

Key Features:
   Smart Query Handling – Understands flexible user inputs.
   Efficient Filtering – Finds recipes in seconds.
   Interactive Responses – Returns clean JSON outputs.

⚙️ How It Works
1. Dataset Preparation
   Loads a Kaggle recipe dataset (~5k recipes).
   Renames columns for clarity (Cuisine, TotalTimeInMins, etc.).

2. Core Functions
   Three key functions power the retrieval system:
   1️⃣ describe_columns() → Explains dataset structure. 
   2️⃣ filter_recipes(condition) → Filters using Pandas queries. 
   3️⃣ filterUniqueValuesOfColumn() → Lists unique cuisines/ingredients.

3. Gemini AI Integration
   Tools are defined for function calling.
   Few-shot prompting helps Gemini interpret queries.
   Dynamic execution runs the right function per request.

4. Example Queries
   ![sample-queries](https://github.com/user-attachments/assets/07d347dc-6a7a-43e0-bca1-47b7d4c6c42c)

🚀 Key Takeaways
   ✔ No more manual filtering – AI handles complex queries. 
   ✔ Natural language support – Ask in plain English.
   ✔ Scalable for larger datasets – Works with 100K+ recipes.

💡 Future Improvements:
  Add image-based recipe search (Gemini Vision).
  Add an Embedding Models and perform FAISS similarity search
  Integrate personalized recommendations and links to youtube videos
  Deploy as a web app.

🎯 Conclusion
    This project showcases how Gen AI + structured data can revolutionize search. Whether you're a home cook or a foodie, AI-powered retrieval makes finding recipes faster and smarter.

What would you like to search for? 🍕🍜🍰
