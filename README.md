# Gen-Ai_-Summarize-Dialogue

Lab 1 - Generative AI Use Case: Summarize Dialogue
In this lab, you will do the dialogue summarization task using generative AI. You will explore how the input text affects the output of the model, and perform prompt engineering to direct it towards the task you need. By comparing zero shot, one shot, and few shot inferences, you will take the first step towards prompt engineering and see how it can enhance the generative output of Large Language Models.


Lab 2 - Fine-tune a generative AI model for dialogue summarization
In this notebook, you will fine-tune an existing LLM from Hugging Face for enhanced dialogue summarization. You will use the FLAN-T5 model, which provides a high quality instruction tuned model and can summarize text out of the box. To improve the inferences, you will explore a full fine-tuning approach and evaluate the results with ROUGE metrics. Then you will perform PEFT fine-tuning, evaluate the resulting model and see that the benefits of PEFT outweigh the slightly-lower performance metrics.


Lab3 : reinforcement learning to generate more-positive summaries
In this notebook, you will fine-tune a FLAN-T5 model to generate less toxic content by Facebook's hate speech reward model. The reward model is a binary classifier that predicts either "not hate" or "hate" for the given text. You will use Proximal Policy Optimization (PPO) to fine-tune and detoxify the model.
