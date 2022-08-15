# Using Spotify API to Analyze Audio Features & Song Popularity

### By: Samuel Hewitt

## Problem Statement
Music streaming services have changed the metrics for a song/artist to be considered successful.

Predict popularity of a song based on it's audio features

## Data:
Work in progress...

## Software Requirements:
All data cleaning and modeling was run in Python using the following libraries:
Pandas, skLearn, matplotlib, Seaborn
Work in progress...

## Data Dictionaries

### Spotify Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**artist_name**|*str*|Spotify|The name of the artist.|
|**artist_genre**|*str*|Spotify|The genre(s) of the artist.|
|**track_name**|*str*|Spotify|The name of the track.|
|**track_id**|*str*|Spotify|The Spotify ID for the track.|
|**popularity**|*int*|Spotify|The popularity of the track. The value will be between 0 and 100, with 100 being the most popular. The popularity of a track is a value between 0 and 100, with 100 being the most popular. The popularity is calculated by algorithm and is based, in the most part, on the total number of plays the track has had and how recent those plays are.|
|**danceability**|*float*|Spotify|Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.|
|**energy**|*float*|Spotify|Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy.|
|**key**|*int*|Spotify|The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.|
|**loudness**|*float*|Spotify|The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typically range between -60 and 0 db.|
|**mode**|*int*|Spotify|Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.|
|**speechiness**|*float*|Spotify|Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.|
|**acousticness**|*float*|Spotify|A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic|
|**instrumentalness**|*float*|Spotify|Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.|
|**liveness**|*float*|Spotify|Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.|
|**valence**|*float*|Spotify|A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).|
|**tempo**|*float*|Spotify|The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.|
|**duration_ms**|*int*|Spotify|The duration of the track in milliseconds.|
|**time_signature**|*int*|Spotify|An estimated time signature. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure). The time signature ranges from 3 to 7 indicating time signatures of "3/4", to "7/4".|

**NOTE:** artist_genre was one-hot encoded for modeling. Doing so changes shape of dataframe from (10,064, 16) to (10,064, 2,588)

## Modeling:

Work in progress...

### Regression Model:

Work in progress...

### Classification Models:

Work in progress...
  
### Clustering:

Work in progress...


## Conclusion:

Work in progress...

## Next Steps:

Repull data periodically as popularity changes day-to-day. 
Errors with API where genre is not present for multiple artists