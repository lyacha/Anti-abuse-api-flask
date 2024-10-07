# Anti Abuse API Flask
API which returns cusswords, can be used to check cusswords in bots or etc.

## Run

```pip install -r requirements.txt```

```py app.py```

## API Endpoints

```/api/v1``` returns all the cusswords.

```/api/v1/check?q={string}``` returns `True` or `False` if the query matches the cusswords in API.

## How to Contribute?

Fork the repository, open **cuss_words.txt** and enter the words in new lines.

Make a **Pull Request**.

You can enter any number of variations.
