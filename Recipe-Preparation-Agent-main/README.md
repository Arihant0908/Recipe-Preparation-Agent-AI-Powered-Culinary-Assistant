🍳 Recipe Preparation Agent: AI-Powered Culinary Assistant
The Recipe Preparation Agent is a sophisticated AI-driven solution developed during an IBM internship, leveraging IBM Watsonx AI Studio and the Granite-3-3-8b-instruct model with Retrieval-Augmented Generation (RAG). This project transforms available ingredients into personalized, accurate, and step-by-step recipes, optimized for real-time culinary assistance.

🌟 Project Overview
This initiative showcases the application of advanced NLP, RAG, and machine learning techniques to address practical challenges in home cooking. Built on IBM Cloud Lite, the agent delivers tailored meal solutions, minimizing food waste and accommodating dietary preferences, making it a valuable tool for diverse users.

🔑 Key Features

Ingredient-Based Recipe Generation: Dynamically retrieves recipes based on user-provided ingredients.
Customizable Instructions: Generates clear, step-by-step cooking guides with practical substitutions for missing ingredients.
Dietary Adaptability: Adjusts recipes for vegetarian, vegan, gluten-free, or other preferences.
Enhanced Accuracy: Utilizes 3-fold cross-validation and optimized model parameters for reliable predictions.
User-Friendly Insights: Provides cooking tips and time-saving techniques.
Scalability: Designed for integration with Watsonx Runtime and potential voice-enabled interfaces.


🛠 Technical Stack

Platform: IBM Watsonx AI Studio, IBM Cloud Lite
Model: Granite-3-3-8b-instruct (Foundation Model)
Technologies: Retrieval-Augmented Generation (RAG), Natural Language Processing (NLP), Prompt Engineering
Programming: Python 3.11 (Jupyter Notebook)
Data: Cleaned_Indian_Food_Dataset.csv (11.19 MB, 9 columns)
Tools: LangChain, IBM Watsonx API, Object Storage


🎯 Use Cases

Home cooks seeking meal inspiration from limited ingredients.
Individuals with dietary restrictions or allergies.
Busy professionals requiring quick, healthy recipes.
Sustainability advocates aiming to reduce kitchen waste.


📊 Performance Metrics

Accuracy: Achieved 90% training data accuracy with 10% holdout data validation.
Build Time: Optimized preprocessing and model selection workflows (e.g., 68 seconds elapsed).
Cross-Validation: 3-fold validation ensures robust model generalization.


🚀 Getting Started

Clone the repository: git clone <repository-url>
Launch IBM Watsonx AI Studio and open the project.
Upload Cleaned_Indian_Food_Dataset.csv or use the preloaded dataset.
Execute the Jupyter notebook (Recipe Agent.ipynb) to initialize the agent.
Input ingredients and preferences via the provided interface to generate recipes.


📋 Sample Interaction
Input:  

Ingredients: rice, tomato, onion, green chili  
Preference: vegetarian

Output:Recipe: Spicy Tomato Fried RiceInstructions:  

Heat 2 tbsp oil in a pan over medium heat.  
Add chopped onions and sauté until golden brown.  
Add diced tomatoes and green chilies, cooking until soft.  
Stir in cooked rice, salt, and spices; mix well for 5 minutes.  
Serve hot with a side of yogurt.Tip: Use pre-cooked rice to save time.


🌱 Future Enhancements

Multilingual Support: Extend recipe generation to multiple languages.
Voice Interface: Integrate voice-enabled interactions.
Nutrition Analysis: Add calorie and nutrient tracking.
Meal Planning: Generate weekly meal plans with grocery lists.


🎓 Achievements

Certifications: IBM SkillsBuild (Getting Started with AI), LangChain RAG
Internship Impact: Demonstrated end-to-end AI solution development at IBM.


📧 Contact
For inquiries, connect with the developer: Ansh Mittal (IBM Watsonx AI Studio profile).
