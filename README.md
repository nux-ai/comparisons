# Large Language Model (LLM) Compilation

### LLMs:
    - https://github.com/Hannibal046/Awesome-LLM
    - https://www.lakera.ai/blog/open-source-llms
    - https://github.com/eugeneyan/open-llms
    - https://sapling.ai/llm/index
    - https://huggingface.co/models

### Evaluations
    - Lorem 

### Data Format

```json
{
    "Model_Name": "gpt-4",
    "Developing_Organization": "OpenAI",
    "Release_Date": "1-12-2023",
    "Parameters": "175b",
    "Training_Data_Size": "Massive dataset including books, websites, and other texts",
    "Language_Support": ["english", "spanish", ...],
    "Minimum_Hardware_Requirements": {
      "CPU/GPU": "High-performance CPU, specifics vary based on usage scenario",
      "RAM": "32GB",
      "Disk": "1TB"
    },
    "Benchmarks": [
        {"HellaSwag": 95.3, "source": "url"},
        ...
    ],
    "Max_Tokens": 10000,
    "Model_Architecture": "Autoregressive language model using Transformer architecture",
    "Research_Paper": "",
    "Use_Cases": [
      "Natural language understanding and generation",
      "Text-based AI applications",
      "Language translation",
      "Content creation"
    ],
    "Performance_Metrics": "High accuracy in language tasks, benchmarks available in research papers",
    "Open_Source": false,
    "API_Availability": true,
    "Cost": {
        "unit": "tokens",
        "interval": 1000,
        "input": 0.03,
        "output": 0.06,
        "source": "https://openai.com/pricing"
    },
    "Energy_Consumption": "Significant; exact figures dependent on usage scale",
    "Ethical_Considerations": "Concerns include potential for biased output, misuse for generating misleading information",
    "License_for_Use": "https://openai.com/policies/terms-of-use"
}
```

### Inspiration
- https://instances.vantage.sh/