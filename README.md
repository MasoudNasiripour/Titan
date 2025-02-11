Pytorch code for Titan paper

In this repo we trying to create a code base or [Titan paper](https://arxiv.org/abs/2501.00663v1)

The authors of this paper, designed a new structure for LLMs that consist of three main component:
  - Long-Term Memory module: this module is gonna save the past information from a long-sequence or a chat-like input and give usefull information about the past to Core module
  - Core Module: This module is gonna process the input with the help of Long-Term Mmory and Persistent Memory. in the forward-path of this module, they store some information into Long-term memory and retrieve some information from that. 
  - Persistant Memory Module: this one is like a pretrained llm that gonna have information about language
