# Bert-Model-Project

Note: You need to download the uncase_L-12_H-768_A-12 BERT model from here to run the single sentence test with model (without fine-tune). Check here to see how to run bert-service.

# Motivation
A 2019 survey conducted by Cisco, 2,601 adults participated, it reveals only 32% of respondents care about privacy policy. Needless to say they would examin the policy thoughly. As more application services emerging, most of the people agree the policy without any consideration. It will aggravate the risks of sharing personal data, although the federal laws or country laws have existing corresponding laws about this. It is still insufficient when we see many news about personal data leaked.
So,  we decide to create an app service to monitor the risk before users or consumers involving it. They can get the risk analysis in few seconds. 

# Introduction
The application service we created is to analyze the privacy policy from any companies and monitor the risk about sharing the personal data to third parties. Through our app service, we predict the risk possibilities in each sentence by the trained model, Bert, a NLP model developed by Google for pre-training language representations, with our label data. Our interface not only clearly shows the risk probability but also offers the filter to let the user clearly see which sentence have more risks. 
