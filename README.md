🚀 Research Grant Evaluation System

A cutting-edge system designed to streamline the evaluation of research grant proposals by combining FAISS for efficient similarity analysis and Llama 3.1 for NLP-driven insights. The system provides actionable feedback to improve proposal uniqueness and boost approval prospects.
🌟 Features

    🔍 Similarity Analysis:
    Identifies and compares proposals against existing projects using vector embeddings.

    🤖 NLP Evaluation:
    Generates detailed insights and recommendations using Llama 3.1's advanced language understanding.

    ✅ Actionable Feedback:
    Highlights innovative aspects, suggests areas for improvement, and assesses grant approval likelihood.

    📊 Comprehensive Reporting:
    Summarized similarity scores and detailed evaluations for easy decision-making.

🛠️ Technologies

    FAISS: Efficient similarity search and indexing.
    LangChain: Framework for integrating LLM capabilities.
    Ollama Embeddings: High-quality vector embeddings for textual data.
    Python: Core language for development and data processing.

📦 Installation

    Clone the repository:

git clone https://github.com/sharrybhatti/research-grant-evaluation.git
cd research-grant-evaluation-system-rag

Install dependencies:

    pip install pandas faiss-cpu langchain-ollama

🚀 Usage

    Prepare Your Dataset: Ensure your dataset includes the following fields:
        Project Title
        Objectives
        Methodology/Activities
        Outcomes (Quantifiable)
        Discipline/Sector

    Set Dataset Path: Update the file_path variable in the script:

file_path = r'path\to\your\dataset.csv'

Run the Script:

python app.py

Input Your Project Proposal:
Provide your project details for evaluation:

    query = """Your project description here."""

📊 Example Output

    Similarity Analysis:

        Identifies overlap and uniqueness of the project with a similarity score for each aspect.

    NLP Feedback:

        Highlights innovative features, redundancy, and areas for improvement.

    Grant Recommendation:

        Provides a clear likelihood score with actionable suggestions to enhance approval chances.

🔮 Future Enhancements

    Add an intuitive web interface for real-time proposal evaluations.
    Expand compatibility for diverse grant domains and larger datasets.
    Integrate advanced visualizations for similarity scores and feedback summaries.

📜 License

This project is licensed under the MIT License.
🙌 Contributions

Contributions are welcome! Please feel free to open an issue or submit a pull request to improve the project.
