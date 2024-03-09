# A Challenge Set for Coreference Resolution

#### The following jupyter notebook files create the challenge sets:
1. `number.ipynb` (creates the challenge set for the capabilities of grammatical number, mention position, and syntactic role)
2. `gender.ipynb` (creates the challenge set for the capabilities of handling gender bias, and dealing with different pronoun types)
3. `nonanaphoric_it.ipynb` (create the challenge set for the capability of identifying cases of non-anaphoric "it")

#### The following jupyter notebook files apply the two examined models to make predictions and evaluate those predictions with the selected tests:
1. `apply_spacy.ipynb` (applies and evaluates the neuralcoref model across all challenge subsets)
2. `apply_bert.ipynb` (applies and evaluates the SpanBERT model across all challenge subsets)

#### The following jupyter notebook extracts and compares the scores from the evaluation of the two models with respect to each challenge subset:
1. `comparison.ipynb`
