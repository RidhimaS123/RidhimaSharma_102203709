# RidhimaSharma_102203709 (Product Recommendation System)

AI-Powered Product Recommendation and Analytics Web AppThis repository houses a full-stack web application developed as an intern assignment. The project demonstrates the successful integration of multiple Artificial Intelligence (AI) domains with modern web development practices to create a robust and intelligent e-commerce solution.The application provides a seamless, conversational recommendation experience for products and a dedicated data analytics dashboard.

Project Overview & Core FeaturesThis project serves as a comprehensive demonstration of expertise across Machine Learning (ML), Natural Language Processing (NLP), Computer Vision (CV), and Generative AI (GenAI), all integrated into a high-performance backend and a modern React frontend.

Product Recommendation Interface (Frontend Route: /)AI-Driven Recommendation: Uses an ML model combined with Vector Database search (embedding-based) to provide personalized and relevant product recommendations.Conversational Experience: The user interface is designed as a "back-and-forth conversation page," allowing for a dynamic and interactive search process.Generative AI Descriptions: Leverages a GenAI model (via LangChain) to dynamically generate creative and unique product descriptions for the recommended items.Computer Vision (CV) Integration: Incorporates a CV model (e.g., for feature extraction or image similarity) to enhance product search and recommendations based on image data.

Data Analytics Dashboard (Frontend Route: /analytics)Visualization: A separate route dedicated to displaying key analytics, charts, and insights for all items in the database.NLP/Text Analysis: Includes features that process product data (title, description, material, etc.) to group similar or related products (e.g., using clustering or topic modeling for segmentation).

Technology StackComponentTechnology / FrameworkDetailsBackend API(Gemini) The core API for serving ML/AI models and data.Frontend UIReact (or preferred UI library)Modern JavaScript library for a responsive and dynamic user experience.Vector DatabasePinecone (preferred) / Milvus / ChromaDBUsed for efficient storage and retrieval of product embeddings.AI OrchestrationLangChainMust be used for GenAI model chaining and embedding-based search workflows.Core MLscikit-learn, PyTorch, TensorFlow (choose one)For the product recommendation model development.NLPspaCy, HuggingFace Transformers)For text analysis, clustering, and feature extraction from product text data.CV, CNN, ResNet, Vision Transformer For image analysis and feature extraction from product images.

Local Setup and InstallationFollow these steps to get the application running on your local machine.Prerequisites npm/yarnGenAI API Key(Gemini) Vector DB Credentials (Pinecone API Key)

pip install -r requirements.txt
npm install
npm start

I have deployed this website on vercel through my github Repsitory.
Basically, in this system we can add items to the cart and get the recommendations of similar items based on selected items.
