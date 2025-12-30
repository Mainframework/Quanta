# Quanta
Convert and quantize llm models

This is an app for windows which allows power users to work with .safetensors models. 

<img width="1218" height="930" alt="Screenshot 2025-11-21 114116" src="https://github.com/user-attachments/assets/0a417f96-223b-47cd-b283-227bf4178cb4" />


It convert models in FP16 or FP32 quite fast
It includes many type of quantization from: q4_k_m,q5_k_m,q6_k,q8_0, F16, BF16, F32, IQ4_NL...

Requirements: Transformers, Torch, Sentencepiece. 

In cmd or powershell do: 
python -m pip install transformers
python -m pip install torch
python -m pip install sentencepiece
