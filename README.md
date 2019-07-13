## Frame Extraction

### Semi-automatic Frame Extraction from FrameNet 
<br/>

##### In our knowledge-attention mechanism, the pre-processing step of extracting relevant frames from FrameNet can be easily done through the following semi-automatic process:
1. automatic frame extraction through frame index keywords matching with relation types and its synonyms automatically obtained from Thesaurus.com;
2. automatic extract all the related frames through inter-frame relations provided by FrameNet;
3. manual verification and remove the irrelevant frames. 

##### The automatic process reduces the search space significantly and the manual verification process ensure that only the relevant knowledge is utilised to avoid introducing noise to our system.

##### Since a relation extraction system normally involves few and limited relation types,  this pre-processing step won't take too long. Besides, it is convenient to add new relations to the existing system by expanding the relation indicators.
