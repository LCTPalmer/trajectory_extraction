# trajectory_extraction
Python implementation of 'Improved Trajectories' video description pipeline : extract trajectories -> cluster -> BoF representation.
<br><br>
Learns a codebook of trajectory features and represents videos with a BoF representation. Parameters are set in
feature_extraction_pipeline.py. It is set up to take two text files - one containing names of training videos and one
containing names of test videos.
<br><br>
Dependencies:<br>
Numpy<br>
scikit-learn<br>
scipy.sparse<br>
Improved (or Dense) Trajectories binary - source available here: 
&nbsp;&nbsp;&nbsp;&nbsp;http://lear.inrialpes.fr/people/wang/improved_trajectories <br>
&nbsp;&nbsp;&nbsp;&nbsp;after compilation, set dt_bin variable in extract_dt.py to the path of the binary.


