*****************************************************
**VEM - the Varieties of English modal sense corpus**
*****************************************************

Created: May 2023

Thank you for your interest in the Varieties of English modal sense corpus (VEM). The data is available at: INSERT URL

The data for this dataset is itself taken from the written component of the International Corpus of English (ICE). For more information on the corpus, please visit https://www.ice-corpora.uzh.ch/en.html

Please be aware that this data is published under a Creative Commons licence for research purposes. The text of the licence can be found in the accompanying text file.


***************
**VEM: Makeup**
***************

VEM consists of data taken from the International Corpus of English (ICE), specifically from seven sub-corpora: the Philippine, Hong Kong, Indian, Jamaican, Irish, and Canadian components of ICE (which are all administered at the University of Zürich; visit https://www.ice-corpora.uzh.ch/en.html for more information), the Sri Lankan component (which is administered at Gießen University; https://www.uni-giessen.de/en/faculties/f05/engl/ling/research/completed/ice), and the Nigerian component (available at https://sourceforge.net/projects/ice-nigeria/). 

From each of these sub-corpora, we have sampled 20 instances each of five modal verbs: can, could, may, must, and should. This makes for a total of eight hundred samples. 

Three annotators have annotated the modal verb sense expressed by the respective modal verbs in each sample. 

VEM is supplied in a simple spreadsheet format (both .xlsx and .csv files are available). The column structure is as follows:

	-variety: the variety of English this is taken from - see the specified sub-corpora above
	-modal: which modal verb the sentence contains
	-sentence: the sentence after undergoing preprocessing (removing punctuation and additional information from the original sentence)
	-a1sense, a2sense, a3senes: the senses each annotator has determined, respectively. An "x" marks instances where an annotator was unable to make a decision.
	-tag: the identifying tag. Use this to retrieve context from the respective ICE corpora (see section below)
	-original sentence: the original, unaltered sentence from the ICE corpora.

**********************************
**ACCESSING THE FULL ICE CORPORA**
**********************************

The full ICE corpora are available upon registration at https://www.ice-corpora.uzh.ch/en.html. 
Access to ICE-Sri Lanka must, at the time of writing, be requested separately (https://www.uni-giessen.de/en/faculties/f05/engl/ling/research/completed/ice). 
Access to ICE-Nigeria is open; it is available at https://sourceforge.net/projects/ice-nigeria/.

******************
**USING THE TAGS**
******************

VEM includes the tags used by ICE to identify utterances and/or documents. As the structure can vary slightly between ICE corpora, we can only give a brief overview here. 
In general, filenames of the ICE corpora consist of those parts of the tags that follow the identifier of the ICE corpus (e.g. "ICE-CAN:" or "ICE-HK:"); for instance, ICE-Canada contains files like "W2E-004" or "W1B-018". These identify the genre and document number:
	
	-W1: non-printed documents
		-W1A: student writings
		-W1B: letters
	-W2: printed documents
		-W2A: academic writing
		-W2B: popular writing
		-W2C: reportage (e.g. news)
		-W2D: instructional writing (administrative; skills and hobbies)
		-W2E: persuasive writing (e.g. editorials)
		-W2F: creative writing (e.g. novels, short stories) 

Please refer to the ICE handbooks for more information.

Following this, the tags contain information about the utterance's position within the document. 

Note that ICE-Nigeria does not adhere to these general rules. Instead, the tags refer to the genre (e.g. "AHum" for academic texts from humanities; "bl" for business letter; "SkHo" for Skills and Hobbies etc.) and the number of the document within the genre.