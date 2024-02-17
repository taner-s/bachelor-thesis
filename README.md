# bachelor-thesis
Code and Dataset for my bachelor thesis

# Code
The code contains the training process of several AI models for the task of multiclass music genre classification. The whole dataset used for the training is also available here. Further details about the implementation can be found in the bachelor thesis.


# Dataset

The dataset contains 13 acoustic features and the lyrics of 15,740 songs divided into 10 genres.


## Feature Description

### Genre:
The dataset contains songs from the Hip-Hop, Jazz, Rock, Pop, Country, Metal, R&B, Indie, Electronic and Folk genres.

### *acousticnes*: 
A confidence measure that represents whether the song is acoustic or not. The variable ranges between 0.0 to 1.0 with a high value describing a high confidence that the song is acoustic.

### *danceability*: 
A measure that represents how suitable a song is for dancing. This feature combines many different acoustic features, such as the tempo, rhythm stability, beat strength and overall regularity. This variable also ranges between 0.0 and 1.0 with a high number describing a song that is more suitable for dancing.

### *durations_ms*: 
The duration of the song in milliseconds.


### *energy*:
A variable describing how energetic a song feels like. A few typical traits of energetic songs are being loud, fast and noisy. Again, the value ranges between 0.0 and 1.0 with a high number labelling a song as more energetic.



### *instrumentalness*:
A variable predicting whether the song contains vocals or not. Values are between 0.0 and 1.0 with a value above 0.5 representing instrumental tracks with no vocals.

### *key*:
A variable that predicts the key the song is in. The values are between -1 and 11. The standard pitch notation is used, which means that 0 = C, 1 = C sharp/ D flat, 2 = D, and so on according to the pattern. If the key cannot be classified, the value is -1.

### *liveness*:
A measurement that predicts whether the recording is a live performance or studio recording. The values are between 0.0 and 1.0 with a value above 0.8 meaning a strong confidence that the recording is a live version. This prediction is done by detecting the presence of a live audience in the record.


### *loudness*:
The average overall loudness across the song measured in decibels(dB). The values typically range from -60 to 0.



### *mode*:
A binary classifying feature that indicates the mode of the song. 1 represents major and 0 represents minor. 


### *speechiness*:
Speechiness describes whether spoken words are detected in a song or not. Values from 0 to 0.33 suggest that the song probably does not contain any spoken words at all. From 0.33 to 0.66, it is likely that a track contains music and words. Values from 0.66 to the maximum of 1 are likely to contain only words.


### *tempo*:
A tempo prediction for the song in beats per minute (BPM).


### *time_signature*:
An estimation of the time signature of a song. The values range from 3 to 7, which represents time signatures from 3/4 to 7/4.


### *valence*:
A value from 0.0 to 1.0 representing how positive a song is perceived. A higher value indicates a more positive sound, which can be described as happy, cheerful or euphoric. A lower valence value indicates more negative songs that can be connected with emotions like sadness, depression or angriness. 

### *Lyrics*:
The lyrics text corpus of a song


