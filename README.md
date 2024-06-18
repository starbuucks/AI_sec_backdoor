# AI_sec_backdoor
This repository contains all of the experimental codes and the results provided from [AI security Final report](https://github.com/starbuucks/AI_sec_backdoor/blob/main/BackdoorWatermarking%20as%20a%20Service.pdf)

## Simple Backdoor Injection (Image LSB Modification)

### Train the model

Experimental Codes
- [Simple_Backdoor-bit-1-epoch-300.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Simple_Backdoor-bit-1-epoch-300.ipynb)
- [Simple_Backdoor-bit-2-epoch-300.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Simple_Backdoor-bit-2-epoch-300.ipynb)
- [Simple_Backdoor-bit-3-epoch-300.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Simple_Backdoor-bit-3-epoch-300.ipynb)
- [Simple_Backdoor-bit-4-epoch-300.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Simple_Backdoor-bit-4-epoch-300.ipynb)
  
Results
- [bit-1-epoch-300](https://github.com/starbuucks/AI_sec_backdoor/tree/main/bit-1-epoch-300)
- [bit-2-epoch-300](https://github.com/starbuucks/AI_sec_backdoor/tree/main/bit-2-epoch-300)
- [bit-3-epoch-300](https://github.com/starbuucks/AI_sec_backdoor/tree/main/bit-3-epoch-300)
- [bit-4-epoch-300](https://github.com/starbuucks/AI_sec_backdoor/tree/main/bit-4-epoch-300)

### Test the model

> At first, experiment was designed to do 110 epochs with a bit position of 3,
> 
> but the validation accuracy for bit position 3 surpassed 0.95 within just 1 epoch
>
> when the train set size was 50,000, decided to test with just 10 epoch.
> 
> _For more details, see Section 5.1 in the [paper](https://github.com/starbuucks/AI_sec_backdoor/blob/main/BackdoorWatermarking%20as%20a%20Service.pdf)._

Experimental Codes
- [Simple_Backdoor-bit-3-epoch-110.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Simple_Backdoor-bit-3-epoch-110.ipynb)
- [Simple_Backdoor-bit-3-epoch-10.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Simple_Backdoor-bit-3-epoch-10.ipynb)
- [Simple_Backdoor-bit-4-epoch-1.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Simple_Backdoor-bit-4-epoch-1.ipynb)

Results
- [bit-3-epoch-110](https://github.com/starbuucks/AI_sec_backdoor/tree/main/bit-3-epoch-110)
- [bit-3-epoch-10](https://github.com/starbuucks/AI_sec_backdoor/tree/main/bit-3-epoch-10)
- [bit-4-epoch-1](https://github.com/starbuucks/AI_sec_backdoor/tree/main/bit-4-epoch-1)

## Improved Backdoor Injection (Message Injection)

### Test the model

Experimental Codes
- [Advanced_Backdoor-1-epoch-1.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Advanced_Backdoor-1-epoch-1.ipynb)
- [Advanced_Backdoor-2-epoch-1.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Advanced_Backdoor-2-epoch-1.ipynb)
- [Advanced_Backdoor-5-epoch-1.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Advanced_Backdoor-5-epoch-1.ipynb)
- [Advanced_Backdoor-10-epoch-1.ipynb](https://github.com/starbuucks/AI_sec_backdoor/blob/main/Advanced_Backdoor-10-epoch-1.ipynb)

Results
- [adv-bckdr-1-epoch-1](https://github.com/starbuucks/AI_sec_backdoor/tree/main/adv-bckdr-1-epoch-1)
- [adv-bckdr-2-epoch-1](https://github.com/starbuucks/AI_sec_backdoor/tree/main/adv-bckdr-2-epoch-1)
- [adv-bckdr-5-epoch-1](https://github.com/starbuucks/AI_sec_backdoor/tree/main/adv-bckdr-5-epoch-1)
- [adv-bckdr-10-epoch-1](https://github.com/starbuucks/AI_sec_backdoor/tree/main/adv-bckdr-10-epoch-1)

