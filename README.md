# Agri-Llama
Presenting an innovative Question Answering (QA) system tailored exclusively for the agriculture industry. This cutting-edge solution is designed to assist farmers by efficiently addressing their queries and information needs.

#### RAG Architecture:

Leveraging the Retrieval-Augmented Generation (RAG) architecture, the system seamlessly combines retriever and generator models. This dual-stage process enhances the system's ability to understand and provide contextually relevant answers to a wide range of queries relevant to farming practices.

#### Llama-2 7B chat LLM and  FAISS (In Memory Vector Store):
To optimize information retrieval, the system employs `Llama-2 7B` and `FAISS` as  an advanced Memory Vector Store. This technology ensures fast and accurate similarity searches, allowing the retriever to extract pertinent information from the extensive agricultural dataset quickly.

#### Hugging Face Dataset:
The QA system is trained and validated using a carefully curated dataset from Hugging Face, specifically tailored to the nuances and complexities of agricultural terminology and context. We have use `Tasfiul/Agricultural-dataset` from Huggingface `datasets` library which consists of `175k rows of Question-Answer` Pairs related to the `agriculture domain`. 

#### Key Features:

Farmers' Assistance: The system is specifically crafted to excel in the agricultural domain, ensuring accurate and contextually relevant responses to queries related to farming techniques, crop management, pest control, and more.
Real-time Responsiveness: Leveraging the efficiency of Llama-2 FAISS, the system provides quick and precise answers, making it a valuable tool for farmers requiring rapid information retrieval.
Scalability: The architecture allows for easy scalability, enabling the addition of more data and features to enhance the system's performance over time.
Applications:

The RAG-based QA system, with its emphasis on assisting farmers, is a valuable tool for those in the agriculture industry, providing reliable and timely insights to enhance decision-making and farming practices.
In summary, this state-of-the-art QA system, empowered by RAG architecture, Llama-2 FAISS, and the Hugging Face datasets, is specifically designed to support and assist farmers in addressing their queries within agriculture's dynamic and complex landscape.

