## TODO

- download commonvoice delta
- create a dictionary/csv for the audio clip and the embeddings and all the metadata for the audios
- run cluster purity experiment
    - check:
        - gender
        - accent
        - age
        - HDBSCAN
        - KMeans


look into: http://github.com/EleutherAI/concept-erasure for debiasing the embeddings? Could be interesting to build a classifier from wav2vec embeddings and then see if it does worse on these new debiased embeddings? would need a different delta split? 