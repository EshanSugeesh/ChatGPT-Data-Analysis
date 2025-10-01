# ChatGPT Data Analysis
## Overview
This project provides an end-to-end workflow for analyzing exported ChatGPT conversations. Leveraging Python, pandas, and NLP tools, the notebook enables users to extract, flatten, and visualize message interaction networks and conversational entities from a conversations.json export file.
## Features
- Load and preprocess ChatGPT conversations.json export.
- Extract message metadata, user/system roles, timestamps, conversation threads.
- Flatten hierarchical message structures for analysis.
- Identify named entities and analyze interaction networks using NLP.
- Export node and edge lists (CSV) for graph-based visualizations.
- Privacy-conscious: No sample data included; user uploads required for analysis.
## How to Use
1. Export your ChatGPT conversation history from [chat.openai.com](https://chat.openai.com/).
2. Download the conversations.json file provided by OpenAI.
3. Open the notebook in Google Colab.
4. Upload your conversations.json via the Colab upload cells.
5. Run through each cell to process, analyze, and export results.
6. Download nodes.csv and edges.csv for further visualization.
7. To visualize the exported nodes.csv and edges.csv, open the included index.html file in your browser. Upload your nodes.csv and edges.csv within the web interface and follow the on-screen prompts for interactive graph visualization.
## Requirements
- Python 3.x (Google Colab-ready)
- pandas, numpy, spacy (installed via notebook cells)
## Privacy & Security
- No personal/chat content is stored in this repository.
- The notebook is designed to process your own uploads and does not include preloaded conversations.
- Always review exported files (nodes.csv, edges.csv) before sharing publicly—they may contain actual message snippets from your uploads.
## License
MIT License
## Author
Eshan Sugeesh ([eshan.sugeesher.phy22@itbhu.ac.in](mailto:eshan.sugeesher.phy22@itbhu.ac.in))
## Tips
- You can mention the exact Colab URL if you want quick notebook launch.
- For extra professionalism, add badges (Colab, MIT License), usage screenshots, and optional advanced features section.
- Include a disclaimer if your project is strictly for educational or personal usage.
