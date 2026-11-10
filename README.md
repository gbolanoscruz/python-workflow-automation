# 🐍 Python Workflow Automation & Observability Script

An enterprise-grade Python automation framework designed to interact with internal APIs (like Jira or ServiceNow), extract operational metrics, and automatically identify system bottlenecks.

## 🎯 Business Objective
In large-scale corporate environments, manually monitoring workflow failures leads to delayed incident response. This script serves as a lightweight **Intelligent Automation** solution that proactively fetches data, analyzes execution times using `pandas`, and logs critical failures—embracing the **"observable by default"** mindset.

## ⚙️ Key Features & Best Practices
- **Enterprise Logging:** Implements the native Python `logging` library for clean, timestamped, and severity-leveled output (crucial for LMA frameworks).
- **Data Analysis:** Utilizes `pandas` to transform unstructured API JSON payloads into structured DataFrames for rapid bottleneck identification.
- **Type Hinting:** Uses Python typing (`List`, `Dict`) for robust, maintainable code.

## 🚀 How to Run Locally

1. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   
2. Execute the automation script::
   ```bash
   python main.py

Built with 💻 by Gustavo Bolaños to eliminate manual toil and optimize business processes.
