# FYDP
Final Year Design Project

<h1 align="center">Abstract</h1>
<p align= "justify">
Creating a system that uses video data to recognize a person’s sign gestures for Bangla sign language (BSL), and translate it into corresponding text and speech in real-time to  acquire the goal of establishing two-way communication using machine learning techniques. The translated sign language gesture will be acquired in the text which is further converted into audio and vice versa. To enable the detection of gestures, we  made use of the “Long short-term memory (LSTM)” algorithm. As language is a vast area that includes an ocean of words, we first target to recognize sign gestures and translate them. To establish the two-way communication system we can use existing studies of text-to-speech and voice recognition and NLP research for implementing the full system. LSTM is used for long-term dependencies and sequence predictions. We have used around 9000 video data for training our model. 
</p>
<h1 align="center">Introduction</h1>
<h3 align="">1.1 Motivation</h3>
<p align= "justify">
In today’s world communication gap between normal people and people with hearing disabilities is very common, especially in Bangladesh. We face difficulties communicating with them because of the lack of knowledge of sign language. We find it difficult to express our conversations properly and don’t even understand what they are saying. Hence comes the urge to establish an easy way to communicate (at least the daily small talks such as greetings, introductions, bargaining in shops, etc) with them without learning sign language.
</p>
<h3 align="">1.2 Social and Ethical Issues</h3>
<p align= "justify">
Our work will enable us to communicate with people with whom we can not communicate normally. This will diminish the barriers to communication between normal people and people with hearing disabilities. Using a system that translates real-time sign gestures is a totally different and new experience to make. So, getting used to the system can be a bit uncomfortable at the beginning, but it will impact socially in the long run. We will also take proper approval from the concerned people so that no ethical issue will arise in the near future.
</p>
<h3 align="">1.3 Environment and Sustainability Issues</h3>
<p align= "justify">
The system we want to use is basically a camera-based system, which can be accessed using a simple smartphone device. So, there is no harm or pressure on the environment. As we all know that language is a vast area to work with. Collecting data for every word is a bit hard o achieve in a year time period. So, our plan was to train our models using semi-supervised learning methods and a continuous process using micro neural networks to train new data. It would make the system more accurate over time and helpful to all. Though we did not use a semi-supervised learning method to ensure the accuracy of our system, we included a module in our system to collect live video data and process it. The continuous learning strategy will keep the sign dictionary up to date always and keep the system sustainable. 
</p>
<h3 align="">1.4 Limitation of Previous Work</h3>
<p align= "justify">
Although we found a lot of work that matches our initial goal, all the works have a basic limitation compared to ours. The biggest limitation of the previous works is there is no such work as we are aiming for. As our goal is to establish a system that recognizes Bangla sign gestures in real time and translates it into text or, speech. The studies on Bangla sign language are limited to digit recognition, character-wise conversion, and character recognition. None of the work represents a system that allows complete communication. The datasets are fingertip and character-based. But the Bangladeshi specially-abled people use a mixture of Bangla sign gestures, English sign gestures, and acting impressions. <br>
Moreover, the number of Bangla sign words in the Bangla Sign Language dictionary is around 800 now and it is increasing day by day. Besides that, Bangla sign gestures are gradually changing, the studies are limited here. The studies that are similar to our work which is recognizing sign language by words or sentences are for American Sign Language, Indian Sign Language, Arabic Sign Language, or other languages. But our main field of interest is to recognize Bangla Sign Language word-wise because conversations are done in sentences or in a meaningful way to express thoughts. And we only can achieve this by recognizing Bangla Sign Language by words or sentences instead of characters. 
</p>
<h3 align="">1.5 Problem Statement</h3>
<p align= "justify">
Bangladeshi people with hearing disabilities use sign gestures to express their emotions and thoughts, which most normal people don’t understand. It is difficult to communicate with them for small purposes like greetings, introductions, bargaining at shops, etc. <br>
Sign language gestures typically include hand shapes, positioning, alignment, movements, and facial expressions to convey meaning [1]. Bangla Sign Language uses metaphoric signs to represent commonly used words or thought expression processes. <br>
Many studies are trying to figure out the solution to recognize sign language using various machine learning techniques, however, not all of them offer a two-way communication method. Besides that, most of these studies only recognize the gestures of only characters which makes them limited in actions, such as, when having a conversation with someone using characterwise, we have to spell each word we want to say which is a very lengthy process and not a feasible or fruitful choice. 
</p>
<h3 align="">1.6 Our Proposed Method</h3>
<p align= "justify">
Our target is to establish a system that allows us to communicate with specially-abled people by recognizing their sign gestures and expressing our talks to them in an understandable way. Though the expressions and emotions are limitless, and that makes our target limited, we are aiming for small conversations like introductions between two people, greetings between two people on the road or in other places, and bargaining at the shops. This does not cover the full scenario but it is a small contribution to making their lives easier and smoother. <br>
So, instead of going for the full-scale system development, we rather work on the recognition of Bangla sign words first, and then we intend to deploy a whole working system to build a tow way communication system. For the initial target, we chose an advanced version of RNN architecture which is LSTM. It is intended to better accurately model periodic sequences and associated long-range relationships than traditional RNNs.<br>
As we did not have enough data for Bangla Sign Language, we developed a system to collect live video data for our system and as well as labeling the data. 
</p>
