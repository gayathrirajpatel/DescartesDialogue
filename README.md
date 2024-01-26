# DescartesDialogue

## Design

> Introduction of team via sign to text and speech simultaneously.
> Sign to text
> Improve text to sign
> Integrate everything seamlessly using Cloudflar's workers
> Complete all of this by 31st jan


## Progress so far

> text to sign using stable diffusion and few customised prompts and show images

## Improvements 

> Only image is shown , Make a proper dashboard to show the text to sign and sign to text translation .
> This has to happen after clicking the help button in main website. 

## Creating virtual environment

```bash
    python3 -m venv venvSign
    source venvSign/bin/activate   # On Windows: .\venv\Scripts\activate
    pip install ipykernel
    python -m ipykernel install --user --name='myenv'
    jupyter notebook
```

- Set up jupyter server password to access the url
- Select jupyter kernel of your environment (myenv)

## Related

 - [How to setup Jupyter Notebook virtual environment vscode kernel] - https://devinschumacher.com/how-to-setup-jupyter-notebook-virtual-environment-vs-code-kernels/
 - https://learn.microsoft.com/en-us/javascript/api/overview/azure/ai-vision-image-analysis-rest-readme?view=azure-node-preview#examples
 - https://github.com/Azure-Samples/azure-search-openai-javascript

## Steps involved

1. Export and Convert Python Model - DONE
2. Host model on Cloud Object Storage - DONE
3. Clone computer vision template - DONE
4. Install and update dependencies - DONE
5. Load graph model from url - DONE
6. Make detections and cleanup - DONE
7. Create drawing function and labelmap - DONE
8. Draw to the canvas using requestAnimationFrame - DONE
