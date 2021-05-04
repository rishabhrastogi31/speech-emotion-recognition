# speech-emotion-recognition

(RAVDESS)
The Ryerson Audio-Visual Database of Emotional Speech and Song
(RAVDESS) contains 7356 files (total size: 24.8 GB). The database
contains 24 professional actors (12 female, 12 male), vocalizing two
lexically-matched statements in a neutral North American accent.
Speech includes calm, happy, sad, angry, fearful, surprise, and disgust
expressions, and song contains calm, happy, sad, angry, and fearful
emotions. Each expression is produced at two levels of emotional
intensity (normal, strong), with an additional neutral expression. All
conditions are available in three modality formats: Audio-only (16bit,
48kHz .wav), Audio-Video (720p H.264, AAC 48kHz, .mp4), and
Video-only (no sound). Note, there are no song files for Actor_18.


here in this project a CNN model was trained and tested with accuracy of 95% wih which we evaluted our input audio file and indentifed emotions from it


***File naming convention***

Each of the 7356 RAVDESS files has a unique filename. The filename consists of a 7-part numerical identifier (e.g., 02-01-06-01-02-01-12.mp4). These identifiers define the stimulus characteristics:

***Filename identifiers***

- Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
- Vocal channel (01 = speech, 02 = song).
- Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
- Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the ‘neutral’ emotion.
- Statement (01 = “Kids are talking by the door”, 02 = “Dogs are sitting by the door”).
- Repetition (01 = 1st repetition, 02 = 2nd repetition).
- Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

Filename example: 02-01-06-01-02-01-12.mp4 

- Video-only (02)
- Speech (01)
- Fearful (06)
- Normal intensity (01)
- Statement “dogs” (02)
- 1st Repetition (01)
- 12th Actor (12)
- Female, as the actor ID number is even.
