 Requirements 
=================

* Remote keyless entry (RKE) systems have become extremely popular.
* The installation rate for RKE systems in new vehicles is more than 80% in North America and more than 70% in Europe.
* Besides the obvious advantages of convenience, RKE-actuated vehicle-immobilization technology minimizes car theft.
* European automakers are incorporating the technology in vehicles in cooperation with insurance companies, who in turn, require it as a condition for acquiring auto insurance.
* That trend began in Germany, and is expected to spread throughout Europe within a few years.
* Remote keyless entry (RKE) has captivated automobile buyers, as evidenced by the popularity of RKE on new automobiles and as an after-market item.
* This application note provides an overview of RKE systems and discusses how they meet requirements such as range, battery life, reliability, cost, and regulatory compliance.
* It shows some circuits and design approaches and offers some predictions for future systems, which will include two-way communications.


 High level Requirements :
=============

| ID    | Description | Category  | 
| -------|------------|-----------|
| HLR01 | User should able to lock the car  | Technical  |
| HLR02 | User should able to unlock the car  | Technical  |  
| HLR03 | User should able to activate alarm | Technical  | 
| HLR04 | User should able to deactivate alarm | Technical  | 
| HLR05 | User should able to approach lights | Technical  |


Low Level Requirements :
=======================
| ID    | Description | Status  |
| ------| ----------- |-----------| 
| LLR01 | STM32 should be able to run on PC   | implemented  |
| LLR02 | Hex file must be run without any error |  implemented  |  
| LLR03 | Delay should be properly added in code |  implemented   | 
| LLR04 | Static keywords are used |  implemented  | 
| LLR05 | Functions to single click  | implemented   |
| LLR06 | Functions to double click |  implemented | 
| LLR07 | Functions to triple click | implemented  |
| LLR08 | Functions to quard click | implemented |




![image](https://user-images.githubusercontent.com/83902823/157860280-b4ad16b1-2be2-4e43-96d3-e965e5be1174.png)


