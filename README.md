# Movie Recommendation System

A Python recommendation-system project that compares popularity, content-based, collaborative-filtering, and matrix-factorization approaches, with a Streamlit interface and a reproducible notebook workflow.

## Highlights

- Evaluates six recommendation approaches using offline ranking metrics.
- The project’s saved comparison report records Item-Based Collaborative Filtering at Precision@10 **0.099** and NDCG@10 **0.122**, versus a popularity baseline Precision@10 of **0.0395**. These are offline benchmark results from the original project run.
- Includes source code, notebooks with outputs cleared, aggregate evaluation summaries, and technical documentation.

## Dataset notice

MovieLens 1M files, transformed datasets, user-level recommendation examples, and trained model binaries are not included. The official GroupLens terms prohibit redistributing the dataset without separate permission and restrict commercial use. Download the dataset from [GroupLens](https://grouplens.org/datasets/movielens/1m/) only after reviewing its [official README and usage terms](https://files.grouplens.org/datasets/movielens/ml-1m-README.txt). The repository’s aggregate metrics are included as project results; they do not include the MovieLens rows.

## Running the project

Install the dependencies with `pip install -r requirements.txt`, obtain the dataset from GroupLens under its terms, and follow the workflow in `notebooks/` and `src/` to generate local processed data and models. The Streamlit app needs those locally generated artifacts before it can run.

## Notes

This is an educational portfolio project. The MovieLens dataset remains subject to GroupLens’s terms and is not relicensed by this repository.

## Dataset citation

If publishing results based on MovieLens 1M, acknowledge GroupLens and cite F. Maxwell Harper and Joseph A. Konstan, “The MovieLens Datasets: History and Context,” *ACM Transactions on Interactive Intelligent Systems* 5(4), Article 19 (2015), DOI: [10.1145/2827872](https://doi.org/10.1145/2827872). Do not imply endorsement by GroupLens or the University of Minnesota.
