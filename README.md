# AURA: Automated Response & Threat Analytics Engine

This project is a proof-of-concept for an AI-powered security engine, built in Python with Scikit-learn and Pandas. It is designed to simulate the "brain" of a modern SASE (Secure Access Service Edge) platform.

# How It Works

The AURA engine operates in a simple, powerful loop:
1.  **Ingest Data:** Analyzes network connections (using the KDD '99 dataset).
2.  **AI Analytics:** A trained Random Forest model classifies the traffic in real-time, detecting threats like 'DOS', 'Probe', or 'R2L'.
3.  **Automated Response:** The engine automatically maps the threat to a specific, pre-defined security policy (e.g., `Block`, `Quarantine`, `Monitor`), simulating an automated response.

# Core Features

* AI-Powered Detection: Uses a `RandomForestClassifier` trained on the KDD '99 dataset to achieve high-accuracy threat classification.
* Policy-Based Automation Demonstrates a real-world orchestration concept by linking AI-detected threats to specific, automated security actions.
* Built in Python: Uses standard data science (Pandas, Scikit-learn) and Python libraries.

# How to Run

1.  **Clone the repository:**
    `git clone https://github.com/shansree-z/AURA-Threat-Engine.git`
2.  **Install dependencies:**
    This project requires Python and the following libraries:
    * `pandas`
    * `scikit-learn`
    You can install them using pip:
    `pip install pandas scikit-learn`
3.  **Run the notebook:**
    Open the `AURA01.ipynb` file in a Jupyter Notebook or Google Colab environment.
    
