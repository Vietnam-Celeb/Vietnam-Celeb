# Vietnam-Celeb: a large-scale dataset for Vietnamese speaker recognition
- This is the repository for the anonymous submission of the Vietnam-Celeb dataset at Interspeech 2023.

- This repository includes four parts of the dataset:

    + Part 0: https://drive.google.com/file/d/1pMuT3DFzSwib7SVcRS8VkDwPuLTsemSG/view?usp=share_link     
    + Part 1: https://drive.google.com/file/d/1xayHt2HRqE1aJ4HvtUT40_9XlgvfDfRY/view?usp=share_link     
    + Part 2: https://drive.google.com/file/d/1MIlM78EbN_J9cApkNes_2_BrFrf8XwMc/view?usp=share_link    
    + Part 3: https://drive.google.com/file/d/1h6Na58DC03p-502B9QpC5Z_FadUwAdNA/view?usp=share_link    

To extract the 4 parts, run the two following codes:
```
zip -F vietnam-celeb-part.zip --out full-dataset.zip
unzip full-dataset.zip
```
- The data folder contains the utterances of every speakers in the dataset, in which each speaker has a folder with its name being the ID of that speaker.

- There are three text files corresponding to the datasets that we have split, as
discussed in the anonymous submission to Interspeech 2023:

    + `vietnam-celeb-t.txt`: list of utterances in the training set of Vietnam-Celeb
    + `vietnam-celeb-e.txt`: Pairs of utterances in the Vietnam-Celeb-E test set.
    + `vietnam-celeb-h.txt`: Pairs of utterances in the Vietnam-Celeb-H test set.

- We also include a TSV file containing the information of every speaker in
the dataset, which include the following attributes:

    + `speaker_id`: ID of the speaker
    + `gender`: gender of the speaker
    + `dialect`: Vietnamese dialect of the speaker
    + `source`: the crawling source of the utterances of a speaker.

