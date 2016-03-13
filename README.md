# Speech Analyzer

This Python program helps to analyze and find verbs, pronouns, adverbs, adjectives, nouns, proper nouns etc in your live recorded speech using Natural Language Processing (NLP), and displays output on the screen, in different color codes listed below.

## Files Description-:

`recognizeliveaudio.py` - It records your voice live, and displays your speech in text format.
<br><br>
`smartaudiotospeech.py` - Records your voice live, Displays your speech in text format, and does the analyzing part, and then displays it in the respective colors. 

## Package Requirements-:

<ol>
<li> Speech Recognition 3.3.3 - https://pypi.python.org/pypi/SpeechRecognition/ </li>
<li> NLTK - http://www.nltk.org/install.html and http://www.nltk.org/data.html both are required to be installed </li>
<li> Termcolor - https://pypi.python.org/pypi/termcolor </li>
<li> PyAudio - http://people.csail.mit.edu/hubert/pyaudio/ </li>
</ol>

It's better to install all these packages in a virtual environment `virtualenv`.

Install these packages first, and just run the python file - `python smartaudiotospeech.py` from the terminal. 

## Color Codes-:

CC	coordinating conjunction - Cyan <br>
CD	cardinal digit - Red <br>
DT	determiner - Cyan <br>
EX	existential there (like: "there is" ... think of it like "there exists") - Cyan <br>
FW	foreign word - Cyan <br>
IN	preposition/subordinating conjunction - Cyan <br>
JJ	adjective	'big' - Grey <br>
JJR	adjective, comparative	'bigger' - Grey <br>
JJS	adjective, superlative	'biggest' - Grey <br>
LS	list marker	1) - Green <br>
MD	modal	could, will - Green <br>
NN	noun, singular 'desk' - Red <br>
NNS	noun plural	'desks' - Red <br>
NNP	proper noun, singular	'Harrison' - Green <br>
NNPS	proper noun, plural	'Americans' - Green <br>
PDT	predeterminer	'all the kids' - Cyan <br>
POS	possessive ending	parent's - Cyan <br>
PRP	personal pronoun	I, he, she - Magenta <br>
PRP$	possessive pronoun	my, his, hers - Magenta <br>
RB	adverb	very, silently, - Blue <br>
RBR	adverb, comparative	better - Blue <br>
RBS	adverb, superlative	best - Blue <br>
RP	particle	give up - Blue <br>
TO	to	go 'to' the store. - White <br> 
UH	interjection	errrrrrrrm - Green <br>
VB	verb, base form	take - Yellow <br>
VBD	verb, past tense	took - Yellow <br>
VBG	verb, gerund/present participle	taking - Yellow <br>
VBN	verb, past participle	taken - Yellow <br>
VBP	verb, sing. present, non-3d	take - Yellow <br>
VBZ	verb, 3rd person sing. present	takes - Yellow <br> 
WDT	wh-determiner	which - Cyan <br>
WP	wh-pronoun	who, what - Magenta <br>
WP$	possessive wh-pronoun	whose - Magenta <br>
WRB	wh-abverb	where, when - Magenta <br>

## Credits-:

Ashutosh Saboo - https://github.com/ashutoshsaboo
