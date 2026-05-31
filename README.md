# Walkthrough to the dataset curation

1. Use the `TR-doi` to retrieve all the articles with the corresponding doi first. You need to prepare the journal ISSN (print) as input. It will automatically extract all the papers punlished on this journal since its inception.
2. With the doi information, use the `TR.ipynb` to extract the full-text data from journal.

## About the Elsevier API usage

### Get your API key

[Elsevier API](https://dev.elsevier.com/)

### Safely use your API key

Put the API key in a file named `config.yaml` in the parent directory `../config.yaml` of this GitHub repo. The content of the file should be like this:

```yaml
elsevier_api:
    api_key: your_api_key_here
```
