## `spotify_data`

- `acousticness` : A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
- `analysis_url` : A URL to access the full audio analysis of this track. An access token is required to access this data.
- `danceability` : Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. 
  A value of 0.0 is least danceable and 1.0 is most danceable.
- `duration_ms` : The duration of the track in milliseconds.
- `energy` : Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.
- `id` : The Spotify ID for the track.
- `instrumentalness` : Predicts whether a track contains no vocals. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. 
  Values above 0.5 are intended to represent instrumental tracks.
- `key` : The key the track is in. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.
- `liveness` : Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
- `loudness` : The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks.
- `mode` : Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
- `speechiness` : Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value.
- `tempo` : The overall estimated tempo of a track in beats per minute (BPM).
- `time_signature` : The time signature ranges from 3 to 7 indicating time signatures of "3/4", to "7/4".
- `track_href` : A link to the Web API endpoint providing full details of the track.
- `type` : The object type.
- `uri` : The Spotify URI for the track.
- `valence` : A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track.