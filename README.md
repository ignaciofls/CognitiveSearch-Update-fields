# CognitiveSearch-Update-fields
Jupyter notebook to create a new field in an index in Azure Cognitive Search, to avoid dropping and rebuilding an index (useful to save time and cost in massive indices)

As indicated in https://docs.microsoft.com/en-us/azure/search/search-howto-reindex there is no way to change certain attributes once the index has been created. This repo dumps the existing data from a field, creates a new field and populates it with that data.
