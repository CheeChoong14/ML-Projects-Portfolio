## Lab_SpeakerDiarizationwithKmeans

This lab enhancement performs speaker diarization, which involves identifying and segmenting different speakers in an audio file using K-means clustering. The audio is first processed by extracting 1-second or 2-second chunks, and then feature embeddings for each chunk are generated using a voice encoder. These embeddings are reduced to two dimensions using t-SNE for visualization. K-means clustering is then applied to group similar chunks (representing individual speakers) based on these embeddings. We also use the elbow method to determine the optimal number of clusters by calculating inertia values for different cluster counts and selecting the "knee" of the curve as the ideal cluster number. Finally, the clustering results are visualized with a scatter plot where each chunk is labeled according to its cluster, allowing for a visual representation of the speakers in the audio.

- Install and Import Libraries
  - librosa
  - resemblyzer  
- First Audio: Two Speaker
  - 1 second chunks
- Second Audio: 3 speakers
  - 1 second chunks
  - Elbow method
  - 2 secomds chunks
- Conclusion
