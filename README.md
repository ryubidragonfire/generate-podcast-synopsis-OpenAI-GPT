# Industry : Media & Entertainment
# Use Case : Generate Podcast Synopsis with OpenAI GPT
This repo illustrates how to use OpenAI GPT to 
- generate a synopsis from a podcast transcription into multiple languages.
- generate 2-3 tag lines based on the podcast content.
- generate serch engine optimised (SEO) keywords.

# Dataset
This example uses the [transcription](https://www.ft.com/content/935ee7eb-e11d-4458-94f6-25e1d0ccd9a2) of [podcast : Why SVB’s collapse is not a 2008 repeat](https://www.ft.com/content/c6fb49cb-20fc-4b8d-b693-9eff09f41580) avaiable from [Financial Times](ft.com) to illustrate how to make use of OpenAI GPT for the use case described above. 

# Notebooks
- [podcast-to-synopsis-taglines-keywords.ipynb](./notebooks/podcast-to-synopsis-taglines-keywords.ipynb) This notebook explores how to split a long podcast transcript into chuncks, generate synopsis, taglines, and search engine optimised (SEO) keywords. 

# Future Work
- Transcribe from audio to text.
   - references: 
      - Speaker diarisation : https://github.com/Azure-Samples/cognitive-services-speech-sdk/blob/master/samples/python/console/transcription_sample.py#L41
      - Supported languages : https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/language-support?tabs=stt#supported-languages
- Cater for large data corpus. 

# Related Repos
Related repos from the author:
- https://github.com/ryubidragonfire/document-analysis-using-gpt-3
- https://github.com/ryubidragonfire/code-explaination-openai
- https://github.com/ryubidragonfire/personalised-movie-reviews-gpt-3 

# References
- OpenAI repo: https://github.com/openai/openai-cookbook/blob/main/examples/Entity_extraction_for_long_documents.ipynb
- Which embedding model to use? https://openai.com/blog/new-and-improved-embedding-model/
- OpenAI models: https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/models
- API reference: https://platform.openai.com/docs/api-reference/completions/create
