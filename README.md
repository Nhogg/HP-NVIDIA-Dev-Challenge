# Mood Mate - AI Powered Journaling Insights
## What it does
Mood Mate provides an intuitive and clean user interface that allows users to create journal entries. These entries are then fed to a bert text classification model which extracts tags based on the input. Then, the entries and those tags are sent to Google's Gemini API. This is where the insights are generated and provided to the user.
## How to use
To run the model, clone the repository and install required packages. Run it inside a Jupyter notebook. 
Due to time constraints and issues with AI Studio and MLFlow, the frontend is not persistently connceted to the model. However, insights from Gemini are available at: https://v0-hp-mh-app.vercel.app/dashboard
To self-serve the model, run all cells in the notebook.
Front end code can be found at: https://github.com/Nhogg/MoodMate

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
