# Movie Recommendation Pipeline

## Description
This project builds an ETL (Extract, Transform, Load) pipeline to process MovieLens ratings and generate movie recommendations. The pipeline extracts data from the MovieLens dataset, transforms it for analysis, and loads it into a format suitable for building recommendation models.

## Tools
- **Python**: Core programming language used for the pipeline.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.
- **Seaborn**: Statistical data visualization.
- **Surprise**: Building and evaluating recommendation systems.
- **Scikit-learn**: Machine learning library for additional data processing.
- **PostgreSQL**: Database for storing and querying transformed data.

## Data Source
The data used in this project is from the [MovieLens Dataset](https://grouplens.org/datasets/movielens/). This dataset contains 32,000,204 ratings and 2,000,072 tag applications across 87,585 movies, created by 200,948 users between January 09, 1995, and October 12, 2023.

## Project Structure
.gitignore etl.ipynb ml-32m/ checksums.txt links.csv movies.csv ratings.csv README.txt README.md

## Usage
1. **Extract Data**: Load the MovieLens dataset files (`ratings.csv`, `movies.csv`, etc.) into Pandas DataFrames.
2. **Transform Data**: Perform data cleaning, merging, and feature engineering to prepare the data for analysis.
3. **Load Data**: Store the transformed data into a PostgreSQL database or use it directly for building recommendation models.
4. **Build Recommendation Model**: Use the Surprise library to build and evaluate collaborative filtering models.
5. **Generate Recommendations**: Predict ratings for users and recommend top-rated movies.

## Notebooks
- **etl.ipynb**: Jupyter notebook containing the ETL pipeline and model building steps.

## License
This project is licensed under the terms specified in the MovieLens dataset usage license. Please refer to the `ml-32m/README.txt` file for more details.

## Citation
To acknowledge the use of the MovieLens dataset in publications, please cite the following paper:
> F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. [https://doi.org/10.1145/2827872](https://doi.org/10.1145/2827872)

## Contact
For any questions or comments, please email [grouplens-info@umn.edu](mailto:grouplens-info@umn.edu).



