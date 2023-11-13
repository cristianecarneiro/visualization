# Project: Visualization 

Visualization project during Ironhack's Data Analytics BootCamp  

![albums](https://github.com/cristianecarneiro/visualization/raw/main/img/albums.jpg)


## Objectives

The goal of this project is to apply the skills we've developed during Ironhacks's Data Analytics BootCamp to create a presentation using data visualization tools 

The data used on this presentation was obtained from a full ETL process in a previous project, available [here](https://github.com/cristianecarneiro/ETL).

It refers to two lists of music albums by the Rolling Stone magazine: 1) Top 500 Greatest Albums and 2) 50 Horrible Albums by Great Artists. This data was enriched with Spotify data on their artists and tracks. 

## Visualization  

The data was interpreted through visualizations using Tableau. To access all charts and the full presentation click [here](https://public.tableau.com/app/profile/cristiane.carneiro/viz/RollingStoneRanking)


## StoryLine 

The output of this project is stored in this repository, as follows: 

<details>
<summary>Top 500 albums</summary>
<br>
The Rolling Stone magazine has an evolving ranking of the 500 Greatest Albums of all time. This list was published for the first time in 2003 by compiling opinions of 200+ critics. The list of then slightly updated in 2012 (the version we are using) and continued to evolve. 
</details>
<br>
<details>
<summary>Horrible 50 albums</summary>
<br>
The magazine has also released an article in 2023 named '50 Genuinely Horrible Albums by Brilliant Artists'. 
</details>
<br>
<details>
<summary>Top 500 albums across time</summary>
<br>
If we look how the '500 Greatest Albums' are distributed overtime, we notice most of them were released in the 60's and 70's. This can indicate those were really 'golden years' for music production, or simply a bias from the the critics towards that particular music genre (i.e., rock, blues). It would be interesting to see how this has evolved in the recent list updates. 
</details>
<br>
<details>
<summary>Top 500 albums across artists</summary>
<br>
The Rolling Stones, Bob Dylan and The Beatles are the three artists with the most albums in the Top 500 list. For each of those artists, it is interesting to analyse the following metrics: 
<br>
<br>
<li> Popularity: The artist's popularity is calculated from the popularity of all the artist's tracks. The popularity of each track is calculated by algorithm and is based, in the most part, on the total number of plays the track has had and how recent those plays are.
<br>
<br>
<li> Number of Followers: The total number of followers in Spotify
<br>
<br>
By looking into those metrics, we can spot some top artists that are 'undervalued' by users (e.g., The Byrds) and some emergent artists that did not have many recognized albums by 2012 but are quite popular per Spotify metrics (e.g., Queen)
</details>
<br>
<details>
<summary>Horrible 50 albums across artists</summary>
<br>
We can look at the same metrics (i.e., popularity and number of followers) for the artists in the 'horrible albums'. Take into account each artists listed here had one album listed
</details>
<br>
<details>
<summary>Tracks' metrics</summary>
<br>
Spotify also provides insteresting metrics at the track level. Here we will analise some metrics (normalized 0-1) from songs from the '550 target albums' from the Rolling Stone magazine, across: 
<br>
<br>
<li> Danceability: how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity
<br>
<br>
<li> Acousticness: whether the track is acoustic
<br>
<br>
<li> Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks
<br>
<br>
<li> Energy: Energy represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale
<br>
<br>
<li> Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration
<br>
<br>
<li> Valence: A measure describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)
<br>
<br>
By playing with the rankings, we can look for 'danceable' songs for a party playlist, 'high valence' songs to cheer one up in sad days, etc. 
<BR>
</details>
<br>
<details>
<summary>Jamming vs Paradise City </summary>
<br>
As an example exercise, we can compare two songs across those metrics: 'Jamming' by 'Bob Marley' and 'Paradise City' by Guns'n'Roses. 
<br>
<br>
We can see how 'Jamming' stands out for 'inviting one to dance' and 'being very positive' (high valance) while 'Paradise City' stands out for being a 'high energy', 'loud' track 
</details>
<br>
<details>
<summary>Bob Marley vs Guns'n'Roses</summary>
<br>
If we extend this analysis to the artists of those songs, we can see that 'Bob Marley' is clearly an artists to 'cheer you up' in 'sad days' while 'Guns'n'Roses' should give you an extra 'energy boost' in lazy days 
</details>
<br>
<details>
<summary>Next Steps</summary>
<br>
The final goal of this exercise is to compare ALL tracks within the '500 Greatest Albums' vs. ALL tracks within the '50 Horrible Albums' to understand how they differ in terms of the 6 metrics describe above. The idea is to understand whether there is an object driver for their choice as a 'top' or a 'horible' album.
<br>
<br>
As of now, the tracks' database is not completed due to requests restrictions in Spotify's API. This exercise will be completed as soon as we got a full database (6000+ songs!) 
</details>

## Repository files  

<li> data: original and cleaned files form the ETL process
<br>
<br>
<li> notebooks: Jupiter notebooks used in the ETL process for extracting, cleaning and preparing the Tableau tables
<br>
<br>
<li> img: Images used in the project 



