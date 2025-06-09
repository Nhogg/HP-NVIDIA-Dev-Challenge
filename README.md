# Mood Mate - AI-Powered Journaling Insights

## 🧠 What It Does

Mood Mate provides an intuitive and clean user interface for journaling. When users submit journal entries, the text is processed by a BERT-based classification model that extracts emotional tags. These tags, along with the entry, are then sent to Google’s Gemini API to generate personalized insights and suggestions for the user.

---

## 🚀 How to Use

1. **Clone the repository** and install the required Python packages.

2. **Run the model locally** inside a Jupyter notebook:
   - The notebook includes cells that load the model, perform classification, and send the data to Gemini.

3. **Frontend access**:
   - Due to time constraints and integration issues with AI Studio and MLflow, the frontend is not persistently connected to the model backend.
   - However, you can explore the UI and view Gemini-generated insights at:  
     🔗 [https://v0-hp-mh-app.vercel.app/dashboard](https://v0-hp-mh-app.vercel.app/dashboard)

4. **To self-serve the model**:
   - Open the Jupyter notebook and run all cells to classify journal entries and generate insights.

---

## 📄 License

Copyright 2025 Nathan Hogg

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
