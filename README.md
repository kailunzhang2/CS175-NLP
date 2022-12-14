## The external libraries our team used with the URL for each Libraries used: 

    • pytorch (https://pytorch.org/)
    • pandas (https://pandas.pydata.org/)
    • emoji (https://pypi.org/project/emoji/)
    • Matplotlib (https://matplotlib.org/)


## The publicly available code we used in our project:

    • CHATBOT TUTORIAL (https://pytorch.org/tutorials/beginner/chatbot_tutorial.html): 
        - Modified & added approximately 140 lines of code
    • Seq2Seq TUTORIAL (https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html)

## The code written entirely by our team:

    All our own newly added functions are in CS175_nlpnet.ipynb.
    
    • Through our research, we added two new datasets found, WikiQA Corpus and Twitter Conversational Corpus.
       We added about 53 lines for preprocessing and merging the vocabulary and the list of pairs.
    
    • For the Seq2Seq model, we started with the basic encoder-decoder model.
    We built the essential model part from scratch(citing several lines to conform to the pipeline) with about 50 lines of code.
    Then we gradually added advanced techniques from tutorials such as the global attention mechanism, teacher forcing, and gradient clipping.

    • For interaction with chatbot, we changed the "evaluateInput" function and added our code.
       We added about 11 lines. The changes we've made provide a better user interface for review participants, 
       while we're better able to collect scores of review participants and prepare scores for visualization. 

    • For User Studies, we wrote ten blocks of codes that represent the survey for 10 participants to start chatting.
       We printed the output of participants' ratings and we plotted them to observe the data distribution.
       We added about 62 lines. 

    • To make the Jupyter notebook that demonstrates important aspects, 
       we added 2 lines about pickles to store the vocabulary.
