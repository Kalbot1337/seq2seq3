# Python Sequence To Sequence, using tensorflow
---
Tensorflow Chatbot for python, using the [sequence2sequence tutorial](https://www.tensorflow.org/tutorials/seq2seq)

---
## What does it do?
---
Well I'm glad you asked! Because it does what the title implies, uses the tensorflow seq2seq tutorial. 

---
## But there are tons of other models out there? Why upload a generic one?
---
Because those models never seemed to work, or they did work, after a week of complicated troubleshooting, setup, training, more troubleshooting. I have created and refined the algorithm so that it works with Tensorflow 1.0.0, and I have only trained this model off my cpu, and after 18 hours at 72000 iterations, I get far better responses then algorithms trained at higher iterations. 

---
## Something doesn't work! What do I do now that I have this error code and a broken bot?!
---

Simple! Submit a ticket in the issues section

---
## That's great, but how does it work?
---

```
git clone https://github.com/b0noI/dialog_converter.git
cd dialog_converter
python converter.py
cd 
cd ./seq2seq3
python ./translate.py  --en_vocab_size=40000 --fr_vocab_size=40000 --data_dir=/home/ubuntu/train --train_dir=/home/ubuntu/train
``` 
