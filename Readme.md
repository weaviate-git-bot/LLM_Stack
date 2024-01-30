# Generative AI Guide book

This repo is my note to the ever evolving Generative AI landscape.

## Terminologies
- Language model
- Large Language Models
- Pretrianed models
- Fine tuning
- Transfer Learning
- Agents
- Prompting
- Reinforcement Learning from Human Feedback
- Embeddings
- Diffusion models
  
## Techniques

### Prompting Techniques
- Zero shot prompting
- Few shot prompting
- Chain of Thought
- ReACT

### Fine tuning Techniques
- PEFT
- LoRA
- SFT

### Policy selection techniques
- [Proximal Policy Optimization(PPO)](https://en.wikipedia.org/wiki/Proximal_Policy_Optimization)
- Direct Preference Optimization (DPO)

## Models
## Language models

### Open source
- Llama
- Llama2
- Alpaca
- Vicuna
- Mistral 7B
- Mixtral 8x7B

### Proprietary models
- Gemini
- GPT models

## Diffusion models
- Stable diffusion
- Denoising Diffusion Probabilistic Model

## Papers

- [Attention is all you need](https://arxiv.org/abs/1706.03762): The paper that introduced the transformer architecture.
- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155): The paper that introduced intructgpt which was ground work for ChatGPT.
- [Learning to summarize from human feedback](https://arxiv.org/abs/2009.01325)
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)
- [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401)
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239): This paper instroduces the **Denoising Diffusion Probabilistic Model** which is used for image synthesis.
- [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020): This paper introduced the [CLIP](https://openai.com/research/clip) model.
- [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/abs/2112.10741): This paper introduced the glide model.
- [Universal Language Model Fine-tuning for Text Classification](https://arxiv.org/abs/1801.06146): This paper introduced the concept of finetuning Language models.
- [A Brief History of Prompt: Leveraging Language Models. (Through Advanced Prompting)](https://arxiv.org/abs/2310.04438)
- [A Comprehensive Overview of Large Language Models](https://arxiv.org/abs/2307.06435)
- [First Tragedy, then Parse: History Repeats Itself in the New Era of Large Language Models](https://arxiv.org/abs/2311.05020): This paper explains the existential crisis that most NLP currently face since the rise of LLMs.

## Technologies

### Libaries
- Langchain
- LlamaIndex
- Huggingface
- [denoising-diffusion-pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch): Implementation of **Denoising Diffusion Probabilistic Model**  in Pytorch.

### Vector databases
- Weaviate
- Pinecone
- ChromaDB

## Blogs
- [DDPM in keras](https://keras.io/examples/generative/ddpm/): This tutorial implements the **Denoising Diffusion Probabilistic Model** in keras.
- [Introduction to Diffusion Models for Machine Learning](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/): Awesome blog bost introducing diffusion models.

## Datasets
- [GLUE, the General Language Understanding Evaluation benchmark](https://huggingface.co/datasets/glue).
- [Wikitext](https://huggingface.co/datasets/wikitext): Contains text extracted from wikipedia.
- [IMDB](https://huggingface.co/datasets/imdb): This dataset is suitable for text binary classification.
- [Yelp review](https://huggingface.co/datasets/yelp_review_full): This dataset is suitable for text multi classification.
- [Text REtrieval Conference (TREC)](https://huggingface.co/datasets/trec): This dataset is for question classification.
- [AG news](https://huggingface.co/datasets/ag_news): This dataset is suitable for topic classification dataset. It contains 1 million news and their corresponding topic as labels. The labels fall into 5 classes.
-  [DPpedia 14](https://huggingface.co/datasets/fancyzhx/dbpedia_14): This dataset contains a subset of DBpedia dataset.


## Companies

|  company  |    Description |     job board|
| :----:    | :-------------:| :------------:|
| [weaviate](https://weaviate.io/) | Vector database company |  [Go to](https://weaviate.io/company/careers#jobs) |
| [Replicate](https://replicate.com/) | Deploys open source models |  [Go to](https://replicate.com/about#join-us) |
| [ChromaDB](https://www.trychroma.com/) | Vector database company |  [Go to](https://trychroma.notion.site/careers-chroma-9d017c3007c7478ebd85bad854101497) |
| [mistral](https://mistral.ai/)| Creators of the Mistral 7B and Mixtral 8x7B models|[Go to](https://jobs.lever.co/mistral?)|

## YouTube Channels

## Podcasts



## Other Resources/Inpirations
The following sites served as the inspiration for this repo.
- [FullStack Python](https://www.fullstackpython.com/): An all in one guide to fullstack development in python.
- [learnprompting](https://learnprompting.org/docs/intro)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [lilianweng blog on prompt engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)

