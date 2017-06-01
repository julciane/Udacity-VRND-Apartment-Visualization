Developer: Carla Julciane dos Santos
Environment: built to Android OS using Google VR SDK version 1.0.3
Time spent in this project: 6 hours

Lightmap Settings:
1-) I activated "Hard shadows" on spotlights, Baked Resolution to 80 and compressed lightmap. The result was that app runned between 60 and 100 FPS as desired, but it presented lighting artifacts.
2-) I activated "Soft shadows" on spotlights, Baked Resolution to 80 and compressed lightmap. The result was that app runned between 60 and 100 FPS as desired, but it presented lighting artifacts.
3-) I activated "Soft shadows" on spotlights, Baked Resolution to 80 and uncompressed lightmap. The result was that app runned between 30 and 60 FPS, but it doesn't present lighting artifacts.
4-) I activated "Hard shadows" on spotlights, Baked Resolution to 80 and uncompressed lightmap. The result was that app runned at 60 FPS as desired, but it didn't presented lighting artifacts (so I choose this option)
Personal impressions:
1-) One thing I liked was learn about baked lightining
2-) It was very challenge to adjust lighting for mobile/unlit shader once I have already adusted it to mobile/difuse.
	This project was particularly difficult for me because there were so many lighting concepts that I was not familiar, so I have to understand the concept and figure out why and how apply them to the scene.
	Another difficult point was the Profiler analysis of how "Lightmap Settings" affects app performance because I often get "App stopping work".