# RAG_for_PDF
针对PDF文档的基于sentence chunks和语义搜索的RAG应用    
RAG_for_PDF能够适用于一系列的PDF文档的查询，并可自行接入外部VectorDB    
1、检索：基于语义搜索搭建Retrieveal system    
2、增强：利用检索到的chunks格式化增强Prompt    
3、生成：接入本地Ollama(QWen:7b)模型，实现带有Meta Source的问答
4、评估：基于references对llm回答进行RAG评估，包括BLEU、Bias得分等    
