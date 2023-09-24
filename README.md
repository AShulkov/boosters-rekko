Rekko Challenge on Boosters.pro platform: https://boosters.pro/championship/rekko_challenge/overview

## Results
In [Top 20 ratings|transactions for all.ipynb]:
- First 20 from top 500 ratings (previously seen movies filtered) - 0.0188299
- Tор 20 movies for all by transactions count (previously seen movies filtered) - 0.0153497

In [Rekko challenge report.ipynb]:
- SVD on ratings enriched by XGB regression predicted - 0.0260726

In [LightFM.ipynb]:
- Matrix factorization on interactions table based only on transactions (cut by watched_ratio) and bookmarks - 0.0294772
- Previous method + top 20 ratings by counts for other users - 0.0296389
