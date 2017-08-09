# wiki
<a href="http://129.199.81.135/cmuworkshop/index.html">The Speaking Rosetta Stone Project</a> is a project of the 2017 <a href="https://www.lti.cs.cmu.edu/2017-jelinek-workshop">Jelinek Speech And Language Technology</a> workshop.  Our goal is to create software that learns the units of a new language (phonemes and words) without the need for any text.  Instead of text, we observe the types of "prompt signals" that a field linguist might use to elicit utterances from the speakers of an unwritten language: images, and translations. For more information, background, and people involved, see the <a href="http://129.199.81.135/cmuworkshop/index.html">Speaking Rosetta Stone project page</a>.

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
<li>Several branches of <a href="https://github.com/neulab/xnmt/">xnmt</a> including:
<ul>
<li><a href="https://github.com/neulab/xnmt/tree/speech_retrieval/xnmt">speech_retrieval</a></li>
<li><a href="https://github.com/neulab/xnmt/tree/linear_encoder/xnmt">linear_encoder</a></li>
<li><a href="https://github.com/neulab/xnmt/tree/lwang114/xnmt">lwang114</a></li>
<li><a href="https://github.com/neulab/xnmt/tree/hidden_states_mingxing/xnmt">hidden_states_mingxing</a></li>
<li><a href="https://github.com/neulab/xnmt/tree/segmenting_encoder/xnmt">segmenting_encoder</a></li>
<li><a href="https://github.com/neulab/xnmt/tree/shrutijpalaskar-patch-1/xnmt">shrutijpalaskar-patch-1</a>, the branch that introduced
attention-matrix visualization reports</li>
<li><a href="https://github.com/neulab/xnmt/tree/subsample-db-ids/xnmt">subsample-db-ids</a></li>
</ul>
</li>
<li>The <a href="https://github.com/iondel/amdtk">Acoustic Model Development Toolkit</a> is one of our baseline unit discovery
systems.</li>
<li><a href="https://github.com/neulab/jsalt-rosetta/">The following results are not public because they include all kinds
of local pathnames that don't generalize,</a> but if you think any of these things would be useful to you, please contact us.
<ul>
<li><a href="https://github.com/neulab/jsalt-rosetta/tree/master/xnmt-config">xnmt config</a> files for flickr8k experiments</li>
<li>Generate a 14x14 grid of CNN-based region vectors for each image using <a href="https://github.com/neulab/jsalt-rosetta/tree/master/vgg16">VGG16</a></li>
<li><a href="https://github.com/neulab/jsalt-rosetta/tree/master/feats2xnmt">feats2xnmt</a>: Convert speech, text, and image features from the format of another package (kaldi, VGG16, etc) into xnmt format.</li>
<li><a href="https://github.com/neulab/jsalt-rosetta/wiki">Private wiki</a></li>
</ul>
</li>
</ul>
