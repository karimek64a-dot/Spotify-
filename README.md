# 🎵 Spotify 2023 Data Analysis | Power BI

## 📌 Project Overview

This project explores Spotify's 2023 music dataset to uncover insights into streaming performance, artist popularity, track characteristics, and music release trends.

Using **Power BI**, I transformed raw music data into an interactive dashboard designed to help users understand what makes tracks successful and how streaming performance varies across artists, years, and musical characteristics.

## 🎯 Project Objectives

* Analyze the streaming performance of tracks and artists.
* Identify top-performing songs and artists.
* Explore music release trends across different years.
* Investigate track characteristics such as Danceability, Energy, Speechiness, and BPM.
* Build an interactive dashboard to communicate insights through data visualization.

## 📂 Dataset Description

The project uses the Spotify 2023 dataset, which contains information about tracks, artists, streaming counts, release dates, and musical characteristics.

### Key Columns

| Column               | Description                            |
| -------------------- | -------------------------------------- |
| `track_name`         | Name of the track                      |
| `artist(s)_name`     | Artist or artists performing the track |
| `released_year`      | Year the track was released            |
| `released_month`     | Month the track was released           |
| `released_day`       | Day the track was released             |
| `streams`            | Total recorded streams                 |
| `bpm`                | Beats per minute                       |
| `danceability_%`     | Danceability score                     |
| `energy_%`           | Energy score                           |
| `valence_%`          | Musical positivity score               |
| `speechiness_%`      | Speech-like content score              |
| `acousticness_%`     | Acoustic characteristics score         |
| `instrumentalness_%` | Instrumental characteristics score     |
| `liveness_%`         | Live-performance characteristics score |

## 🛠️ Tools & Technologies

* **Power BI Desktop** — Dashboard development and data visualization.
* **Power Query** — Data cleaning and transformation.
* **DAX** — Measures and calculations.
* **Data Modeling** — Organizing the dataset and creating a date dimension.
* **CSV** — Source data format.

## 🔄 Project Workflow

### 1. Data Preparation

* Imported the Spotify dataset into Power BI.
* Reviewed column data types and data quality.
* Prepared the release-date fields for time-based analysis.
* Organized the data for reporting and visualization.

### 2. Data Modeling

* Created a Date Dimension (`Dim Date`) using release-date information.
* Added a Date ID to support date-related analysis.
* Prepared the model for analyzing tracks by release date.

### 3. DAX & Measures

Developed measures to analyze key performance indicators, including:

* Total Tracks
* Total Streams
* Total Artists
* Average Streams per Artist
* Best Performing Artist
* Total Streams by Release Year

Additional measures can be used to rank tracks and compare performance across different categories.

### 4. Dashboard Development

Designed an interactive Power BI dashboard with a modern dark-green visual theme.

The dashboard focuses on:

* Overall streaming performance.
* Track and artist analysis.
* Release-year trends.
* Musical characteristics.
* Top-performing tracks.

## 📊 Key Performance Indicators (KPIs)

| KPI                        | Purpose                                                                                    |
| -------------------------- | ------------------------------------------------------------------------------------------ |
| Total Tracks               | Measures the number of tracks included in the analysis                                     |
| Total Streams              | Shows the combined recorded streams                                                        |
| Total Artists              | Measures the number of distinct artists                                                    |
| Average Streams per Artist | Evaluates average streaming performance per artist                                         |
| Best Performing Artist     | Identifies the artist with the highest value according to the selected performance measure |

##
