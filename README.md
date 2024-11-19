# Vibe Check

This project aims to take key features from audio tracks and classify their moods using a machine learning algorithm. 
Since the dataset contained a lot of songs, it would be difficult to go through and label enough to use as training data, so the best option
was to use an unsupervised machine learning algorithm, since it does not require previous labels on the dataset.

This was a semester-long project utilizing the AI/ML material and tools learned within the AI4ALL Ignite accelerator workshops: 
- *Developed an unsupervised machine learning model to determine the mood of the track based on key audio features, e.g., energy, danceability, tempo*
- *Applied the K-Means clustering algorithm to group songs into mood categories*
- *Demonstrated proficiency in Python techniques and data analysis methodologies using libraries such as pandas, matplotlib, and scikit-learn*


## Problem Statement <!--- do not change this line -->

This project was brought about by the universality of music and its impact on societies. Additionally, a majority of people claim that music is integral to his or her
mental wellbeing. As a result, there is an increasing demand for personalized music experiences.  


## Key Results <!--- do not change this line -->

1. Cleaned and normalized a datset of 11,960 songs before spliting the data into a training group and a testing group
2. Established the key features used in determining a song's mood, such as **energy**, **acousticness**, and **valence**
3. Identified four general clusters within the dataset:
   - *Cluster 0: Calm*
   - *Cluster 1: Energetic*
   - *Cluster 2: Happy*
   - *Cluster 3: Sad*
4. Visualized the relationship between song features to reveal the mood
5. Provided a groundwork for later work in a mood-based recommendation system and playlist generation


## Methodologies <!--- do not change this line -->

Engineered a Python script to classify the songs into four general moods. Utilized pandas to load and group songs with similar features using pandas.


## Data Sources <!--- do not change this line -->

*MusicOSet: [Link to MusicOSet Dataset](https://zenodo.org/records/4904639)*


## Technologies Used <!--- do not change this line -->

- **Python** for scripting, data analysis, and machine learning
- **pandas** for reading a spreadsheet into a DataFrame
- **numpy** for calculating on the dataset
- **matplotlib** for creating data visualizations
- **seaborn** for creating pairplots
- **sklearn** for scaling and clustering data
  - **StandardScalar** to scale the data for clustering
  - **train_test_split** to split the data into training (80%) and testing (20%) sets
  - **KMeans** to implement the K-Means clustering algorithm
  - **Silhouette Score** to evaluate the cluster quality
- **Microsoft Excel** to prepare the dataset before loading into Python
- **Jupyter Notebook** for interactive coding and visualization


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- Kionna Kanoyton ([GitHub](https://github.com/KioKano))
