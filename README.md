# trajectory_extraction
Trajectories description of videos : extract trajectories -> cluster -> BoF features for each video.
<br><br>
Dependencies:<br>
Numpy<br>
scikit-learn<br>
scipy.sparse<br>
Improved (or Dense) Trajectories binary - source available here: http://lear.inrialpes.fr/people/wang/improved_trajectories.
After compilation, set dt_bin variable in extract_dt.py to the path of the binary.

<br>
<br>
Learns a codebook of trajectory features and represents videos with a BoF representation. Parameters are set in
feature_extraction_pipeline.py. It is set up to take two text files - one containing training videos and one
containing test videos.
