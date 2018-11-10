-- Take out later
# Follow this: 

http://course.fast.ai/lessons/lesson11.html as of minute 4
http://forums.fast.ai/t/part-2-lesson-11-wiki/14699

This is the prereq:
lesson 6: http://course.fast.ai/lessons/lesson6.html
http://forums.fast.ai/t/wiki-lesson-6/9404

http://localhost:8892/notebooks/ALPNotebook/Artificial%20Language%20Processing.ipynb#Initial-Model

/Users/bherudek/Desktop/deep learning
jupyter notebook

CHECK THIS: https://code.fb.com/developer-tools/getafix-how-facebook-tools-learn-to-fix-bugs-automatically/
---
# Introduction

This article describes, how we can re-use techniques from translating natural languages like english to german for translating artificial languages, used by computers into each other. Specifically, we will use the example of two SQL (standard query language) dialects (mysql and ?) on two different data models based on the fast.ai UML fit model ….

While the resulting translations are an interesting technical result in itself, the main benefit is that we can automate, how applications will exchange data.

## What we will Show
## Why it Matters
### Integration 

Applications store their data in different formats, typically in different formats like tables or files. Different Databases have different Data models (names of tables, fields and relations between tables), while often semantically they refer to the same concepts. For example an Enterprise Resource Planning like SAP has a concept of a Client, a Customer Relatioship Management System like Salesforce holds Data about the very same client. However, the representation of the Client differs technically. In practice syncing such Systems is a painful, manual exercise, which constitutes a large market and even give a part of the Technical Consulting Industry the name ‘System Integrators’. 

The high costs linked to translating different dataformats often lead to centralisation: to avoid the process it is best to stick with one vendor. Also, in the internet the lack of Automation adds to the rise of dominant platforms. If smaller players, lets say a social network, could seamlessly connect to each other, arguably they would be able to easier create the (in-)famous network effects necessary to grow, that is we would see ‘winner takes it all’ scenarios.

The approach might just as well be used to translate typical data exchange formats like XML or JSON into each other. Also, such translations could help translating generic algorithms and libraries. The complexity of the latter might put this rather on the roadmap for a later stage. The former use-case will actually need to make a lot of assumptions about the intention of a message between applications. Message can be meant to acknowledge another message was received, that can mean ‘update my bank account’ / ‘send an email’ / ‘print a report’ ‘run a batch job’ and so on. ‘Intents’ just like self - consciousness is nothing Artificial Intelligence is even close to achieve. Contrary to popular culture, where e.g. a Terminator seems to be self consciousness, we really have no idea how to achieve that. Artificial Intelligence in the Form of Neural Networks for Language Translation is about pattern recognition based typically labelled data reflecting the past.
Instead of making lots of different assumptions on intentions, it is easier to make one generic assumption ‘Sync as much data as possible’ What to do how to ‘interpret’ that data is then entirely up to the receiving algorithm, that might be a conventional algorithm or a smart learning algorithm like a neural network.

### Decentralisation

This might be controversial, but it was the authors initial motivation and is still a valid point.
Quote your own article, reference the ethereum folks.

https://cointelegraph.com/news/why-ethereum-style-blockchains-do-not-really-decentralize

While Bitcoin as a payment system is clearly decentralising such that we do not need Banks in payment traffic, I I doubt using a crypto platform to build a generic application form (‘programmable money’) is a good idea. The problem is that this implies, exaclt one programming model or for that matter one programming model the ethereum community deems feasible is the ‘one blockchain to rule them all’. But we do not want one blockchains (whatever the usecases maybe beyond offering a potentially censor resistant platform), we do not even want one kind of Application platform dominating. That sounds all too familiar from facebook, google and the likes - just the kind of ‘data-banks’ any bitcoin inspired mentality shound want to elimiante. Ethereum - notwithstanding the good intentions of the founding community - therefore amounts to nothing other than a dystopian form of a developer and community monopoly and it is not clear what we win over a CEO and capital dominated platofrm. The real way to achieve decetralisation is to not build an application platform but rather platform that would be able integrating different applications of any kind. Hence, the real de-centralisation problem is one of letting applications - that run on whatever cloud or on premise platform the founders choose - communicate seamlessly. A problem to which this article tries to contribute towards a solution.

### Artificial Social Intelligence

Turing test should demand: two Turing machines can figure out a way to communicate. This approach here helps passing that.

https://www.csee.umbc.edu/courses/471/papers/turing.pdf
## Approach

### The Data set

https://www.w3schools.com/python/python_mysql_create_db.asp


## Summary

We showed, how techniques from natural language processing can be used to process artificial languages. We worked along the example of different SQL dialects on slightly differing Data Models. Two major differences two Natural Languages: It is easy to generate pairs of semantically equal statements in both languages. It is easy to check that the resulting statements are well formed according to the syntactic rules of the language. A specific challenge is the proper handling of variables, i.e. values shall never change in the translation process.
Typical use cases can be found in Application Integration, i.e. connecting two Databases from an ERP and CRM Application and syncing data automatically. In the long run, other use cases e.g. supporting translating java libraries into python code be feasible. Translating artificial languages into each other is  contribution also to the question, whether Machines can acquire full intelligence as arguably that would entail Machines can communicate automated and self-learning, without manual intervention of humans to translate their language representations

## References

http://nlp.fast.ai/category/classification.html

https://arxiv.org/abs/1801.06146

Neural program synthesis
https://arxiv.org/abs/1802.02353


Translations

Which one is later and what matters more?

https://github.com/fastai/fastai/blob/master/courses/dl2/translate.ipynb
https://github.com/fastai/courses/blob/master/deeplearning2/seq2seq-translation.ipynb



http://course.fast.ai/lessons/lesson10.html as of min.16.40
http://course.fast.ai/lessons/lesson11.html


https://github.com/fastai/courses/blob/master/deeplearning2/spelling_bee_RNN.ipynb

https://github.com/fastai/courses/blob/master/deeplearning2/seq2seq-translation.ipynb


https://github.com/fastai/courses/blob/master/deeplearning2/translate.ipynb
https://github.com/fastai/courses/blob/master/deeplearning2/translate-pytorch.ipynb


Some prep & background:
http://course.fast.ai/lessons/lesson4.html  as of min. 1:23.30 
	http://forums.fast.ai/t/wiki-lesson-4/9402

https://github.com/fastai/fastai/tree/master/courses/dl1
Language Modelling: https://github.com/fastai/fastai/blob/master/courses/dl1/lang_model-arxiv.ipynb
https://github.com/fastai/fastai/blob/master/courses/dl1/lang_model.ipynb

https://github.com/fastai/fastai/blob/master/courses/dl1/lesson4-imdb.ipynb
https://github.com/fastai/fastai/blob/master/courses/dl1/lesson6-rnn.ipynb
https://github.com/fastai/fastai/blob/master/courses/dl1/lesson6-rnn.ipynb

History NLP milestones: http://ruder.io/a-review-of-the-recent-history-of-nlp/

Nice graphics to understand attention:https://distill.pub/2016/augmented-rnns/

Grammar as a foreign language: shows how neural net is better than rule based systemhttps://arxiv.org/abs/1412.7449

