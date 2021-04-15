# VideoSummarization
Video summarization methods, code and dataset.

## Methods
For all the methods, the output produced are:
<ul>
  <li><strong>NomeVideo_K.txt</strong>: text file where are indicated the frames selected;</li>
  <li><strong>NomeVideo_K_storyboard.png</strong>: image with all the frames selected;</li>
  <li><strong>NomeVideo_K_skimvideo.mp4</strong>: video skim produced;</li>
  <li><strong>NomeVideo_K_skimvideo.pkl</strong>: pickle file that contain the selected frames for the evaluation purpose.</li>
</ul>
The K parameter is the number of cluster considered. Obviusly, for method the don't produce video skimming or keyframes the file are not produced.

<h1>Uniform Sampling</h1>
This script, produce a video storyboard with a simple techniques of frame sampling. Specified the number of keyframe to extract (K) or the % of video frames to extract, the algorithm takes the K (or %) frames equidistant in the video. For the production of video skim, a number of frame before and after the keyframe are considered. This method is valid as baseline.

<h1>VSUMM</h1>
<h2>Based on frames</h2>
<h3>KEYFRAME_VSUMM</h3>
VSUMM method with color space features for produce video storyboard and video skimming (that are not based on the scene analysis but only on the keyframe). For the production of video skim, a number of frame before and after the keyframe are considered.
<h2>Based on Scenes</h2>

<h1>DeepRes</h1>

## Dataset
<h1>SumMe Dataset</h1>
<h1>TvSum Dataset</h1>

## Evaluation Method

# Results



