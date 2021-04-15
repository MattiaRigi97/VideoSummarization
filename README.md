# VideoSummarization
Video summarization methods, code and dataset.

Video Summarization is a process of creating and presenting, an abstract view of entire video within a short period of time and paying attention to the important contents. Video summarization methods attempt to abstract the main occurrences, scenes, or objects in a clip in order to provide an easily interpreted synopsis.

# Methods
For all the methods, the output produced are:
<ul>
  <li><strong>NomeVideo_K.txt</strong>: text file where are indicated the frames selected;</li>
  <li><strong>NomeVideo_K_storyboard.png</strong>: image with all the frames selected;</li>
  <li><strong>NomeVideo_K_skimvideo.mp4</strong>: video skim produced;</li>
  <li><strong>NomeVideo_K_skimvideo.pkl</strong>: pickle file that contain the selected frames for the evaluation purpose.</li>
</ul>
The K parameter is the number of cluster considered. Obviusly, for method the don't produce video skimming or keyframes the file are not produced.

<h2>Uniform Sampling</h2>
This script, produce a video storyboard with a simple techniques of frame sampling. Specified the number of keyframe to extract (K) or the % of video frames to extract, the algorithm takes the K (or %) frames equidistant in the video. For the production of video skim, a number of frame before and after the keyframe are considered. This method is valid as baseline.

<h2>VSUMM</h2>
<h3>Based on frames</h3>
<h4>KEYFRAME_VSUMM</h4>
VSUMM method with color space features for produce video storyboard and video skimming (that are not based on the scene analysis but only on the keyframe). For the production of video skim, a number of frame before and after the keyframe are considered.
<h2>Based on Scenes</h2>

<h2>DeepRes</h2>

# Dataset
<h2>SumMe Dataset</h2>
<h2>TvSum Dataset</h2>

# Evaluation Method

# Results



