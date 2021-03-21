# MZ 인공지능 해커톤 대회
## AI - NLU with STT (Speech to Text)
[MZ NLP link][https://www.mzhackathon.co.kr/mz/]

using KcBERT to intent classification in self-driven car system

# Data
targets : 대분류(_large.txt) / 중분류(_mid.txt) / 소분류(_small.txt)
training 3 kinds of classes independently, and then multiply their probability to get final classes

# Tokenizer
based on sentensepiece 

# DOCKER
* docker build:

    docker build -t nlp_mz_yhstudy:latest .

* make docker container:

    docker run -it --name yhstudy -v (your directory path):/workspace nlp_mz_yhstudy /bin/bash

# Results
71.868%