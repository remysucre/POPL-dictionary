# The POPL Dictionary

**This dictionary is designed to be crowd-sourced. Please consider contributing!**

## Preface

### Motivation

This dictionary is a resource for people attending [POPL](https://en.wikipedia.org/wiki/Symposium_on_Principles_of_Programming_Languages). The conference spans a huge range of topics, but also reaches great technical depth for each topic. 
As a result, many attendees, especially junior students, can be easily overwhelmed because they lack the necessary background knowledge. 

This dictionary hopes to provide concise, self-contained introductions to various basic concepts frequently used at POPL. 
We hope the dictionary can help you understand POPL talks a little bit better! 

### How to use this dictionary

Simply search for a term you'd like to understand. If it is missing, please open an issue! 

### How to contribute

Both experts and novice can contribute to any topic! 

If you tried to look up a topic but found it missing, file an issue and request the topic to be added. 
Please search the open issues first, and if it is already there, upvote the issue to help us triage. 

If you are a seasoned researcher, you can see if there is an open ticket related to your area of expertise, 
and open a pull request to add that entry to the dictionary. 

If you have experience editing / maintaining similar dictionaries / wikis, feel free to make suggestions on how to
improve this dictionary! 

### How to make an entry

Each entry should be as concise and self-contained as possible. 
While we shall avoid formalism to ease understanding, we should attempt to be rigorous. 

---

### Non-interference

Non-interference is a property about programs that take confidential data as input. 
If such a program also produces publicly visible output, 
 we must ensure the public output does not reveal information about the secret input. 
Non-interference achieves this by forbidding the secret input to affect the public output
 in any way at all. 
Formally, any two program executions differing only on the secret input must produce identical 
 public output. 

For example, suppose the age of the patients at a hospital is confidential information. 
Consider a program that publishes statistics about the hospital population. 
If this program publishes the average age of all patients, it would violate non-interference, 
 because changing the age of a patient (secret) may change the average (public). 
 
 ### Probablistic Programming Languages (PPL)
 
A PPL is a domain-specific language designed for probablistic inference. 
The programmer write a program in the language to define a generative model, 
 then the PPL automatically turns the generative model into an inference engine. 

For example, a programmer may write a program modeling how viruses may lead to 
 different symptoms, perhaps by simulating how each virus interacts with the body. 
Then, the PPL uses this model to produce an inference engine that identifies 
 possible viral infections given observed symptoms. 
