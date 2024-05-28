# MicrosoftProject

实现了一种将非形式化 Latex 数学问题转化为形式化 Lean 4 代码的系统，包括自动形式化和神经定理证明。

引入了符号系统反馈、检索增强 (RAG)、DSP(Draft-Sketch-Prove)、思维链 (Chain-of-Thought)、小样本学习(Few-Shot)、正例反馈等技术。

需要GroqAPI：

https://groq.com/

需要另外两个仓库：

https://github.com/rahul3613/miniF2F-lean4

https://github.com/leanprover-community/repl

以及3个HuggingFace模型：

https://huggingface.co/kaiyuy/leandojo-lean4-tacgen-byt5-small

https://huggingface.co/kaiyuy/leandojo-lean4-retriever-byt5-small

https://huggingface.co/kaiyuy/premise-embeddings-leandojo-lean4-retriever-byt5-small/tree/main
