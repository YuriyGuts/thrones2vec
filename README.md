# Thrones2Vec

Using Word2Vec to explore semantic similarities between the entities of "A Song of Ice and Fire" ("Game of Thrones").

## Trained model

Instead of training your own Word2Vec, you can use an existing trained model from the [Releases](https://github.com/YuriyGuts/thrones2vec/releases) page.

Run this cell in the IPython Notebook:

`w2v.Word2Vec.load(os.path.join("trained", "thrones2vec.w2v"))`
