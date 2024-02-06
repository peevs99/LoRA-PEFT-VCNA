# Leveraging LoRA-PEFT in LLMs for Efficient Training of Virtual Career Navigation Assistants (VCNAs) with Specialized Knowledge


## 🚨 Please refer to the ipynb for code and pdf for explanations.


Virtual Career Navigation Assistants (VCNAs) have the potential to revolutionize 
the way individuals navigate their careers by providing personalized guidance and 
support. By providing personalized career advice and support, VCNAs can help 
individuals make informed decisions about their careers, achieve their goals, and 
increase their overall satisfaction with their work lives. However, developing 
effective VCNAs poses a significant challenge due to the need for large language 
models (LLMs) with specialized knowledge and the ability to adapt to individual 
user needs.

![image](https://github.com/peevs99/LoRA-PEFT-VCNA/assets/88054944/ec962ef3-c51a-4023-bd92-36c5329c7356)

Traditional fine-tuning methods for LLMs can be time-consuming and 
computationally expensive, making them impractical for developing VCNAs that 
can be deployed on a large scale. Additionally, traditional fine-tuning methods can 
result in models that are over-fitted to the training data and do not generalize well 
to new situations.

To address these challenges, this project proposes the use of Parameter Efficient 
Fine-Tuning LoRA (LoRA-PEFT) to train a Falcon 7B LLM for VCNAs. LoRA-
PEFT is a novel fine-tuning technique that enables efficient adaptation of LLMs to 
new tasks while minimizing the number of parameters required. This makes 
LoRA-PEFT a promising approach for developing VCNAs that can be deployed 
on a large scale and that can generalize well to new situations.

References
[1] LoRA:Low-Rank Adaptation of Large Language Models - https://arxiv.org/abs/2106.09685
[2] Efficient Fine-Tuning with LoRA: A Guide to Optimal Parameter Selection for Large Language Models - https://www.databricks.com/blog/efficient-fine-tuning-lora-guide-llms
[3] Finetuning LLMs with LoRA and QLoRA: Insights from Hundreds of Experiments - https://lightning.ai/pages/community/lora-insights/
[4] Low-Rank Adaptation of Large Language Models (LoRA) - https://huggingface.co/docs/diffusers/main/en/training/lora
