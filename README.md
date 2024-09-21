# Tuesday 24/09/3034

Anatomy of RAG 
Search 
optional: search data ingestion using a notebook 
Basic excercises: chat completion. embeddings and similarity, search methods 

chat UI with gradio 
putting it all together 

install streamlit and demo app: https://docs.streamlit.io/get-started/installation/command-line 
streamlit chat app tutorial: https://docs.streamlit.io/develop/tutorials/llms/build-conversational-apps 


to debug `streamlit` apps, add the follow to your `launch.json` file: 

```json
{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Python Debugger: streamlit Module",
            "type": "debugpy",
            "request": "launch",
            "module": "streamlit",
            "args": ["run", "${file}"],
        }
    ]
}
```

https://github.com/Azure-Samples/openai/blob/main/Basic_Samples/README.md



https://farzzy.hashnode.dev/exploring-llamaindex-workflows-a-step-by-step-guide-to-building-a-rag-system-with-azure-ai-search-and-azure-openai?source=more_articles_bottom_blogs 



https://github.com/openai/openai-cookbook/tree/main/examples

https://www.gradio.app/guides/gradio-and-llm-agents or https://docs.streamlit.io/develop/tutorials/llms/llm-quickstart

https://huggingface.co/blog/inference-endpoints-llm

https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-metrics-built-in

[​pptx icon L22_RAG.pptx](https://studentutsedu-my.sharepoint.com/:p:/g/personal/antonette_shibani_uts_edu_au/ERTcd3BRZytBvVRwUUVo3ZUBeIlfAzsvPqZPumIVng_BMA?e=ucMG1B&xsdata=MDV8MDJ8bXV0YXouYWJ1Z2hhemFsZWhAbWljcm9zb2Z0LmNvbXxiYjUzZWU5OTMxODU0Y2ZmYjNlMzA4ZGNjYjA0ZDYxY3w3MmY5ODhiZjg2ZjE0MWFmOTFhYjJkN2NkMDExZGI0N3wxfDB8NjM4NjA4NDY4ODkzOTk4Njg0fFVua25vd258VFdGcGJHWnNiM2Q4ZXlKV0lqb2lNQzR3TGpBd01EQWlMQ0pRSWpvaVYybHVNeklpTENKQlRpSTZJazFoYVd3aUxDSlhWQ0k2TW4wPXwwfHx8&sdata=R1VMci94RE00VS8xd05WSmJ4VldsRzN2WVVtYS9hZjZ2NUhYd0tqcjg2Zz0%3d)

[​pptx icon 02.neural-language-modeling.pptx](https://studentutsedu-my.sharepoint.com/:p:/g/personal/antonette_shibani_uts_edu_au/ETCmw9pRL9tEkL6cV-drpWUBVJ4Q0uHz0iQMqlb5DZirCA?e=VAqfU3&xsdata=MDV8MDJ8bXV0YXouYWJ1Z2hhemFsZWhAbWljcm9zb2Z0LmNvbXxiYjUzZWU5OTMxODU0Y2ZmYjNlMzA4ZGNjYjA0ZDYxY3w3MmY5ODhiZjg2ZjE0MWFmOTFhYjJkN2NkMDExZGI0N3wxfDB8NjM4NjA4NDY4ODk0MDA3MzU3fFVua25vd258VFdGcGJHWnNiM2Q4ZXlKV0lqb2lNQzR3TGpBd01EQWlMQ0pRSWpvaVYybHVNeklpTENKQlRpSTZJazFoYVd3aUxDSlhWQ0k2TW4wPXwwfHx8&sdata=MEYyajdDanR1VmhNRVlTWUE2bitEelN0Q3VJV2tvNlRVMGg0RWducW1DMD0%3d)