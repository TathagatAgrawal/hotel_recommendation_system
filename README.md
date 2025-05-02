# Hotel Recommendation System

This repository implements a content-based hotel recommender that ingests a natural-language travel description and returns the top 10 hotels whose aggregated review "tags" best match the query. The system uses a simple set‐intersection similarity, offering transparent and low-latency recommendations from a corpus of more than 515,000 reviews across 1,493 European hotels.

The dataset used is available at [Kaggle](https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe).

For detailed methodology, experiments, and theoretical background, see the [Jupyter Notebook](Hotel_Recommender_System.ipynb) and the [full documentation](Hotel_Recommendation_System.pdf).

## License

MIT
