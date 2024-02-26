# LLM Capstone Projects
This repository contains several cool open-source limited-scope capstone projects I'm working on to grow my hands-on expertise on LLMs.

**1. Chandler-BOT:** This model is developed as a tribute to my favorite character "Chandler" from the popular American Sitcom "FRIENDS". I gathered the whole script of all 10 seasons of FRIENDS, and collected Chandler's dialogues. I then fine-tuned a sharded version of LLama2-7b from TinyPixel/Llama-2-7B-bf16-sharded available in HuggingFace. I fine-tuned it via AutoTrain using PEFT to make it learn how Chandler talks with humor, wit and fun. The model is available [nafisneehal/chandler-bot](https://huggingface.co/nafisneehal/chandler-bot) through HuggingFace. I am currently working on (i) improving it's performance, and (ii) writing a quick FLASK app to deploy this model through HEROKU. `LLM` `HuggingFace` `Llama 2 7B` `FineTune` `AutoTrain`
**2. GenAI AWS Projects:** 3 Capstone projects completed in Pytorch for GenAI AWS MOOC.
  - Dialog Summarization: In-Context (Zero/One/Few Shot) Learning via prompt engineering, worked with FLAN-T5, tweaked generative configuration parameters for inference (e.g. max_new_tokens, temperature, do_sample, top_k, top_p etc)
  - Fine Tune FLAN T5 for Dialog Summarization: Full Instruction Fine-Tuning, PEFT (LoRA), evaluated using ROUGE metrics
  - Fine Tune FLAN T5 to detoxify Summaries: Fine-tune FLAN T5 with RL (Proximal Policy Optimization) and Meta AI's RoBERTa based hate speech model for content moderation.
