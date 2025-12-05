# Overview
KG-VulMiner, a novel, end-to-end framework that combines knowledge graphs with multimodal large language model (MLLM) for automated vulnerability discovery.

The overall system architecture and workflow are as follows:
```md
-------------- Project ---------------  Raw   -------------   Infor.  ------------  Reports   ------------
| LLM-Powered|  Call   |  K.G.-based |  Vul.  | MLLM-based|  Enhanced |   Vul.   |----------->|   Vul.   |
| Call Graph |-------->|  Vul. Call  |------->|  Function |---------->| Analysis |            |   PoC    |
| Construct  |  Graph  | Graph Query |  Call  |  Analysis |    Call   |   Agent  |<-----------|   Agent  |
-------------- in K.G. --------------- Graphs -------------   Graphs  ------------  Feedbacks -----------—
   Step 1                   Step2                 Step3                 Step4-1                  Step4-2
```


# Demo
- [Vulnerability Analysis Agent Demo](demo/vulnerability_analysis_agent_demo.mp4)
- [Vulnerability PoC Agent Demo](demo/vulnerability_poc_agent_demo.mp4)