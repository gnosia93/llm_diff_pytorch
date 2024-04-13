* https://learn.deeplearning.ai/courses/finetuning-large-language-models/lesson/1/introduction

* [Boost Fine-Tuning Performance of LLM: Optimal Architecture w/ PEFT LoRA Adapter-Tuning on Your GPU](https://www.youtube.com/watch?v=A-a-l_sFtYM)
```
00:00 PEFT source code (LoRA, pre-fix tuning,..)
01:53 Llama - LoRA fine-tuning code 
04:39 Create PEFT - LoRA Model (Seq2Seq)
08.29 LoRA configuration
10:05 Trainable parameters of PEFT - LoRA model
13:09 get_peft_model 
14:21 PEFT - LoRA - 8bit model of OPT 6.7B LLM
15:25 load_in_8bit 
16:30 INT8 Quantization explained 
18:08 Fine-tune a quantized model
22:56 bfloat16 and XLA compiler PyTorch 2.0
25:20 Freeze all pre-trained layer weight tensors
27:52 Adapter-tuning of PEFT - LoRA model
30:50 Save tuned PEFT - LoRA Adapter weights
31:30 Run inference of new PEFT - LoRA adapter - tuned LLM
32:57 Load your Adapter-tuned PEFT - LoRA model
```


* [How to finetune your own Alpaca 7B](https://www.youtube.com/watch?v=LSoqyynKU9E)

* https://github.com/tloen/alpaca-lora