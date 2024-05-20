# Generative AI for research data processing tasks

This repository contains notebooks and data from an exploratory study of the use of generative AI in research data processing.

We explore three research projects which involve complex data processing tasks: 

1. **Seedlists**: We extract plant species names from historical seedlists (catalogues of seeds) published by botanical gardens. This is an *information extraction* task.  
2. **Health Technology Assessment (HTA) documents**: We extract certain data points (name of drug, name of health indication, relative effectiveness, cost effectiveness, etc.) from documents published by HTA organisations in the EU. This is also an *information extraction* task. 
3. **Kickstarter**: We assign industry codes to projects on the crowdfunding website Kickstarter. This is a *text classification* task.
   
## Project Structure

```
.
├── .gitignore
├── LICENSE
├── README.md
├── seedlists               
│   ├── data         
│   └── notebooks           
├── hta               
│   ├── data         
│   └── notebooks   
├── kickstarter               
│   ├── data         
│   └── notebooks 
```

## License

This project is licensed under the terms of the [MIT License](/LICENSE).
