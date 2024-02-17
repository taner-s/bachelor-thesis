# bachelor-thesis
Code and Dataset for my bachelor thesis



# Dataset

The dataset contains 13 acoustic features and the lyrics of 15,740 songs divided into 10 genres.


## Feature Description

### *Lyrics*: 
The songtext of the song

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
A variable that predicts the key the song is in. The values are between -1 and 11. The standard pitch notation is used, which means that 0 = C,   1 = C sharp/ D flat, 2 = D, and so on according to the pattern. If the key cannot be classified, the value is -1.

