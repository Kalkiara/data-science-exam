# data-science-exam
Repository for the exam in Data Science, Prediction, and Forecasting:  

- Does Culture Loop? An Exploratory Investigation of Spotify Audio Features in Hit Songs Over Time.

## Project Organization
The organization of the project is as follows:

```
├── README.md                               <- The top-level README for this project
├── data                                    <- Folder containing audio features -- scraped for top songs between 1960-2022
|   ├── top_songs_by_month.csv              <- Dataset used for the exam
|   └── top_songs_by_year.csv               <- Yearly dataset not used for the exam
├── scraping                                <- Folder containing scraping scripts (client id and secret required for running)
|   ├── scrape_spotify_per_month.ipynb      <- Notebook for monthly scraping
|   └── scrape_spotify_per_year.ipynb       <- Notebook for yearly scraping
├── src                                     <- The main folder for analysis
|   └── analysis.Rmd                        <- R markdown file containing the full analysis
└── datasci_exam.pdf                        <- Corresponding data science paper
```
