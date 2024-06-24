# Prompt Injection Attacks against LLMs

I wrote this SOK seminar paper as a part of the '[Security of Machine Learning](https://intellisec.de/teaching/2023-ws/hot-secml/)'-seminar @KIT. In this paper, I compare several attack types against LLMs and introduce a novel taxonomy to allow the categorization of attacks against LLMs along three dimensions: 
1) Attack Vector
2) Mode of Operation
3) Goal of the Attack

You can find the PDF under [print.pdf](print.pdf).

## Abstract
Large Language Models (LLMs) have gained huge popularity in recent years. 
Being widely available to the public, these Natural Language Processing models can answer human-written input prompts with output prompts hard to distinguish from human-written answers.
Since so many people use LLMs daily, they can carry sensitive user data or be used to trick benign users.
Thus, they also attract the attention of adversaries, who are interested in sensitive data, causing damage to the model or benign users, or simply love chaos.
A straightforward way to attack a LLM is the so called prompt injection which attacks the LLM with user-given input. 
Currently, there is a lack of categorization for these types of attacks. 
Without a categorization, it is hard to prevent attacks on a wide scale or implement countermeasures.
Hence, in this paper, we introduce a taxonomy for prompt injection attacks against LLMs.
To do so, we analyze well-known prompt injection attacks against LLMs and split the attacks into three fundamental parts: The attack vector, the mode of operation, and the goal of the attack. 
Then, we split each of those parts into multiple subcategories to allow a fine-grained categorization of attacks. 
Using our taxonomy, we achieve a wide coverage of (possible) prompt injection attacks against LLMs, allowing categorization and comparison.
Furthermore, we glance at possible defense mechanisms and discuss our taxonomy to ensure the security of LLMs against prompt injection attacks.

In case you want to talk about the paper, feel free to reach out to me!
