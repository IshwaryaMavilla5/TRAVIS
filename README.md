

# TRAVIS: Transformer-Based Help Desk for Visually Impaired Agents

**TRAVIS** (Transformer-based Assistance System) is an AI-powered help desk application designed to assist visually impaired bank service agents by processing user queries using Transformer-based models. It includes:

- 🧠 A Query-Response model for understanding and answering customer queries  
- 🌐 A Translation model for converting between English and Telugu  
- 🔗 A combined API layer to integrate both models into a deployable service  
- 💻 A Frontend interface for user interaction  

---

## 📁 Project Structure

<pre><code> ``` TRAVIS/ ├── backend/ # API logic (Flask/Node.js/etc.) │ └── api.py # Connects both models and handles API endpoints │ ├── models/ │ ├── query_response/ # Query-response model code and artifacts │ │ ├── query_model.ipynb │ │ └── dataset.json │ │ │ ├── translation/ # English-Telugu translation model │ │ ├── translation_model.ipynb │ │ └── dataset.txt │ │ │ └── combined/ # Integrated logic for both models │ └── TRAVISTestingFinal.ipynb │ ├── frontend/ # React or basic HTML/CSS frontend │ └── src/ │ └── App.jsx # User interface │ ├── .gitignore ├── .gitattributes └── README.md # You're reading this ``` </code></pre>
