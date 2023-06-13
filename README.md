# Training-LLMs-Towards-Holistic-Learning
Training Language Models From Fragmentation Learning To Holistic Learning

## Motivation
Large-scale data and Pretrain--Supervised Fine-Tuning--RLHF (Reinforcement Learning from Human Feedback) learning approach advance the performance of Large Language Models (LLMs) on a wide range of NLP tasks. These LLMs trained with enormous documents usually learn fragmentation knowledge, paying attention to the accurate understanding and memory of each knowledge point. The Supervised Fine-Tuning and RLHF approaches facilitate them invoke stored scattered knowledge to produce answers for human queries. It's like teaching a student to learn various skills and be capable of proficient mastery and application of each skill. Hence, we regard the current learning scheme of LLMs as the fragmentation learning. Contrast to fragmentation learning, to our knowledge, the holistic learning is a more comprehensive learning strategy, which starts from a complete learning object and aims to make the young learner (e.g., students or LLMs) come to the solution by step-by-step planning. That is, the young learner develops a detailed learning plan based on the overall objectives and its stored knowledge, gradually completing the final objective. Hence, when a new compositional problem is given, LLMs trained in this way will develop a solution plan by themselves and gradually solve the original problem, such as know what knowledge to learn, what questions should be considered, seek advice from whom, what information should be obtained, what experiments should be conducted.

```
Holistic learning is the opposite of rote memorization. Instead of learning through force, your goal is to create webs of information that link together. --Scott H Young
```

## Method

This is only a simple proposal, anyone could use this for your research. Of course, I am willing to seek cooperation.

Take a simple approach as the example.

To achieve this goal, we present a central processing language models, named CenterLM capable of developing corresponding solution plans for various tasks and recursively recalling the fragmentation knowledge memory from knowledge sources to complete the task. 

Specifically, CenterLM first learns how to decompose the given task into several learning sub-objects under the guidance of humans. 

Afterwards, it will learn to gain the useful experience from knowledge source such as LLMs in different professional fields, calculator, or various modality processors, and update its own information seeking memory. 

By  achieving small decomposed objects, CenterLM finally absorb all information to gain the final solution. 


## Evaluation

Experimental scenarios: Out-Of-Distribution Question Answering, Book Continuation, Strategy Reasoning, and Video Understanding.
