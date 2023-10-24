---
library_name: peft
---
# Model Use:
The following model has been trained to be a marketing tool. It is trained to suggest ways Steve Jobs(The master of technnology marketing) would market a product. 
Inference scripts need to be written separately. 
Fine-tuned version of - NousResearch/Llama-2-7b-chat-hf

Primary Sources: 
https://deci.ai/blog/fine-tune-llama-2-with-lora-for-question-answering/


## Training procedure


The following `bitsandbytes` quantization config was used during training:
- load_in_8bit: False
- load_in_4bit: True
- llm_int8_threshold: 6.0
- llm_int8_skip_modules: None
- llm_int8_enable_fp32_cpu_offload: False
- llm_int8_has_fp16_weight: False
- bnb_4bit_quant_type: nf4
- bnb_4bit_use_double_quant: False
- bnb_4bit_compute_dtype: float16
### Framework versions


- PEFT 0.4.0
