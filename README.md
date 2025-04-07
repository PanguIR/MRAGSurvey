# MRAGSurvey


> A collection of papers and resources related to Large Language Models. 
>
> The organization of papers refers to our survey [**"A Survey on Multimodal Retrieval-Augmented Generation"**](![MRAGSurvey](Source/MRAGSurvey.pdf)). 
>
> Please let us know if you find out a mistake or have any suggestions by e-mail:  chenchong55@huawei.com
>
> (we suggest ccing another email meilang1@huawei.com meanwhile, in case of any unsuccessful delivery issue.)
>
>
> If you find our survey useful for your research, please cite the following paper:

```
@article{MRAGSurvey,
    title={A Survey on Multimodal Retrieval-Augmented Generation},
    author={Lang Mei, Siyu Mo, Zhihan Yang, Chong Chen},
    year={2025},
    organization={GitHub},
    url={https://github.com/PanguIR/MRAGSurvey},
}
```

## Overview of MRAG

### MRAG1.0

The architecture of MRAG1.0, often termed "pseudo-MRAG", closely resembles traditional RAG, consisting of three modules: Document Parsing and Indexing, Retrieval, and Generation. While the overall process remains largely unchanged, the key distinction lies in the Document Parsing stage. In this stage, specialized models are employed to convert diverse modal data into modality-specific captions. These captions are then stored alongside textual data for utilization in subsequent stages.

![MRAG1.0](Source/MRAG1.0.jpg)

### MRAG2.0

The architecture of MRAG2.0 retains multimodal data through document parsing and indexing, while introducing multimodal retrieval and MLLMs for answer generation, truly entering the multimodal era.

![MRAG2.0](Source/MRAG2.0.jpg)

### MRAG3.0

MRAG3.0 architecture integrates document screenshots during the document parsing and indexing stages to minimize information loss. At the input stage, it incorporates a Multimodal Search Planning module, unifying Visual Question Answering (VQA) and Retrieval-Augmented Generation (RAG) tasks while refining user query precision. At the output stage, the Multimodal Retrieval-Augmented Composition module enhances answer generation by transforming plain text into multimodal formats, thereby enriching information delivery.

![MRAG3.0](Source/MRAG3.0.jpg)

## Table of Contents

Coming......


## Paper List

Coming......
