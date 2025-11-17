### FIRST FRONTIER Model 
This project utilizes Frontier language models to summarize maintenance logs generated with realistic data from Perplexity.  
It transforms extensive maintenance records into concise, actionable summaries for easier understanding and reporting.

***

### Project Structure  
```
/frontier-maintenance-summary
|-- README.md              # Project documentation
|-- /code                  # Python scripts and notebooks
|   |-- main.py            # Main summarization pipeline
|   |-- utils.py           # Helper functions
|-- /data                  # Sample or generated log data
|   |-- maintenance_log.json
|-- /results               # Generated summaries and evaluation outputs
|   |-- summary_output.txt
```

***

### Features  
- Leverages Frontier language models for high-quality text summarization  
- Processes synthetic maintenance logs generated via Perplexity API or datasets  
- Modular Python codebase for easy updates and customization  
- Produces summaries geared toward operational efficiency and review  

***

### Setup and Installation  

1. Clone the repository:  
   ```
   git clone <repo-url>
   ```
2. Create and activate a virtual environment:  
   - Linux/Mac:  
     ```
     python -m venv env
     source env/bin/activate
     ```
   - Windows:  
     ```
     python -m venv env
     .\env\Scripts\activate
     ```
3. Install required packages:  
   ```
   pip install -r requirements.txt
   ```

***

### Usage  

1. Run the main summarization pipeline:  
   ```
   python code/main.py
   ```
2. Ensure your Frontier/OpenAI API key is set in environment variables.  
3. Modify or replace the data file `data/maintenance_log.json` to summarize your own logs.  
4. Summaries will be saved to `results/summary_output.txt`.  

***


