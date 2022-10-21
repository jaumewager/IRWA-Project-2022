# IRWA-2022-part-1
In order to run the code, you will have to download the .ipynb file in this repository, and open it in an environment such as Google Colaboratory.
Once the project is opened, you can upload manually the two data files that were provided by the teachers (the tw_hurricane_data.json file and tweet_document_ids_map.csv).
Then, you will have to do three little changes in the code:
- comment the very first cell (from google.colab import drive \n drive.mount('/content/drive')). You won't be using this cell since you will be uploading the data files manually (we think this is the simplest way to run 'external' projects in the google colab).
- change the docs_path = '/content/drive/Shareddrives/RIAW/data_part1/tw_hurricane_data.json' by docs_path = 'tw_hurricane_data.json' in the Load data into memory step
- and the mapping_doc = '/content/drive/Shareddrives/RIAW/data_part1/tweet_document_ids_map.csv' by mapping_doc = 'tweet_document_ids_map.csv', wihch is located after the build_terms(line,stopwords) function.
Once all this changes has been made and the files are correctly uploaded, then you just have to press the button Runtime -> Run all, wait a couple seconds, and you will see the final result.
