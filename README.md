# wiki
<a href="http://129.199.81.135/cmuworkshop/index.html">The Speaking Rosetta Stone Project</a> is a project of the 2017 <a href="https://www.lti.cs.cmu.edu/2017-jelinek-workshop">Jelinek Speech And Language Technology</a> workshop.  Our goal is to create software that learns the units of a new language (phonemes and words) without the need for any text.  Instead of text, we observe the types of "prompt signals" that a field linguist might use to elicit utterances from the speakers of an unwritten language: images, and translations.

Software and data created by this project include:
<ul>
<li><a href="https://github.com/JSALT-Rosetta">Public JSALT-Rosetta Data and Software</a>
<ul>
<li><a href="https://github.com/JSALT-Rosetta/SpeechCoco">The SpeechCoco Database</a></li>
<li><a href="https://github.com/JSALT-Rosetta/evaluation_tools">Evaluation Tools</a>, including ABX unit evaluation tools, and 
train/dev/test splits for flickr8k-speech, mscoco-speech, and the 8k-mscoco subset</li>
<li><a href="https://github.com/JSALT-Rosetta/jsalt-rosetta-2017/tree/master/speech2image">speech2image Tensorflow implementation</a></li>
<li><a href="https://github.com/JSALT-Rosetta/jsalt-rosetta-2017/tree/master/vgg_features">VGG features</a></li>
<li><a href="https://github.com/JSALT-Rosetta/Results">Some results</a></li>
</ul></li>
<li>The <a href="https://github.com/neulab/xnmt/tree/speech_retrieval/xnmt/">speech_retrieval branch of xnmt</a></li>
<li>The <a href="https://github.com/iondel/amdtk">Acoustic Model Development Toolkit</a> is one of our baseline unit discovery
systems.</li>
<li><a href="https://github.com/neulab/jsalt-rosetta/">Results that are not (yet?) public</a>
<ul>
<li><a href="https://github.com/neulab/jsalt-rosetta/tree/master/xnmt-config">xnmt config</a> files for flickr8k experiments</li>
<li>Generate a 14x14 grid of CNN-based region vectors for each image using <a href="https://github.com/neulab/jsalt-rosetta/tree/master/vgg16">VGG16</a></li>
<li><a href="https://github.com/neulab/jsalt-rosetta/tree/master/feats2xnmt">feats2xnmt</a>: Convert speech, text, and image features from the format of another package (kaldi, VGG16, etc) into xnmt format.</li>
<li><a href="https://github.com/neulab/jsalt-rosetta/wiki">Private wiki</a></li>
</ul>
</li>
</ul>
