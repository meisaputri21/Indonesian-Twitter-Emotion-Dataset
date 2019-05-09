# Indonesian-Twitter-Emotion-Dataset

This dataset contains 4.403 Indonesian tweets which are labeled into five emotion classes: love, anger, sadness, joy and fear. 

## Data Format
Each line consists of a tweet and its respective emotion label separated by semicolon (,). The first line is a header. For a tweet with coma (,) inside the text, there is an quote (" ") to avoid column separation.  </br>
The tweets in this dataset has been pre-processed using the following criterias:
1. Username mention (@) has been replaced with term *[USERNAME]*
2. URL/hyperlink (http://... or https://...) has been replaced with term *[URL]*
3. Sensitive number, such as phone number, invoice number and courier tracking number has been replaced with term *[SENSITIVE-NO]*  

## Pre-trained Word Embedding
We have trained 1 Millions Indonesian tweets into Word2Vec and FastText vector. Those pre-trained word embedding can be downloaded [here](https://univindonesia-my.sharepoint.com/:f:/g/personal/mei_silviana_office_ui_ac_id/EkwS7R4C2F9FnYHVLvvkmeoBGRpJ3abNa7Lti9ceG2TWFw?e=dRzvmG).

## Citation
If you want to publish a paper using this dataset and pre-trained word embedding, please cite this publication: <br />
**Mei Silviana Saputri, Rahmad Mahendra, and Mirna Adriani, "*Emotion Classification on Indonesian Twitter Dataset*", in Proceeding of International Conference on Asian Language Processing 2018. 2018.**


## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
