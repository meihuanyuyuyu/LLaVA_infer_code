## Filtered dataset for VQA testing
### mistral-7b

query = "Return the answer only. Do not return any output descriptions or explanations, only the answer. " + question 0.56

query = "Only return information extracted from the raw <image>. Do not return any output descriptions or explanations, only the answer." 0.55

query = "Only return information extracted from the raw material. Do not return any output descriptions or explanations, only the key answer.  " 0.57

query = "Only return information extracted from the raw material. Do not return any output descriptions or explanations, only the key answer. The output answer is strictly consistent with the raw material. Here is the question: " 0.558


### Vicuna-13b
query = "A chat between a curious human and an artificial intelligence assistant. The assistant gives helpful, detailed, and polite answers to the human's questions. USER: <image>\n Only return information extracted from the raw material. Do not return any output descriptions or explanations, only the key answer.  " 
0.69166666666667