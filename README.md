# NLP-Project
Course project for KU NLP course 

This project is created by Andreas Melbye and Mathias Nygaard Larsen

To run our project, follow these steps:

Upload the translated_data folder to /content/drive/MyDrive/, on your Google Drive
such that you have /content/drive/MyDrive/translated_data/...

Ensure you have GPU access, and run the following notebooks:

- week36.ipynb
- week37.ipynb
- week38.ipynb
- week39.ipynb
- week39_questions_only.ipynb
- week39_only_on_answer_inlang.ipynb
- week40.ipynb

For week 41, we do not have a specific notebook, but instead import our test.json from translated_data
and do inference on this test set in each of the notebooks.

If the notebooks do not run, install the required dependencies using

!pip install -r requirements.txt

Install further dependencies using

!pip install [packagename]

if Colab asks for other packages. This may happen with evaluate, or other metric related packages.
