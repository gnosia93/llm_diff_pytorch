* https://learn.deeplearning.ai/courses/finetuning-large-language-models/lesson/1/introduction


### LoRA ###
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
* [PEFT LoRA Explained in Detail - Fine-Tune your LLM on your local GPU](https://www.youtube.com/watch?v=YVU5wAA6Txo&list=PLgy71-0-2-F0pjx9R09G_ACYTfsYJtuyg&index=8)
  ```
  AdapterHub and HuggingFace's new PEFT library focus on parameter-efficient fine-tuning of transformer models
  (LLM for language, Stable Diffusion for images, Vision Transformer for vision) for reduced memory size
  ```

* [Stanford's new ALPACA 7B LLM explained - Fine-tune code and data set for DIY](https://www.youtube.com/watch?v=j6dqO2dSF9c&list=PLgy71-0-2-F0pjx9R09G_ACYTfsYJtuyg&index=9)

### .. ###

* [How to finetune your own Alpaca 7B](https://www.youtube.com/watch?v=LSoqyynKU9E)

* https://github.com/tloen/alpaca-lora

* [Fine Tune Large Language Model (LLM) on a Custom Dataset with QLoRA](https://dassum.medium.com/fine-tune-large-language-model-llm-on-a-custom-dataset-with-qlora-fb60abdeba07)  


## Pytorch Distributed Training ##

* [Distributed package으로 Multi-Node Multi-GPU 학습 알아보기](https://csm-kr.tistory.com/89)
* [PyTorch Distributed Training](https://leimao.github.io/blog/PyTorch-Distributed-Training/)
* [Part 5: Multinode DDP Training with Torchrun (code walkthrough)](https://www.youtube.com/watch?v=KaAJtI1T2x4&t=266s)

* https://devocean.sk.com/blog/techBoardDetail.do?ID=164779&boardType=techBlog

## 참고자료 ##

* https://www.youtube.com/playlist?list=PLgy71-0-2-F0pjx9R09G_ACYTfsYJtuyg