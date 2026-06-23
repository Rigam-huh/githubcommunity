
The selected model, **all-MiniLM-L6-v2**, is distributed through the Hugging Face Model Hub. Although the project does not directly use the Hugging Face API, the SentenceTransformers library automatically downloads the pretrained model from Hugging Face during its first execution.

The workflow is:

```text
Repository Description + README
                │
                ▼
SentenceTransformer
(all-MiniLM-L6-v2)
                │
                ▼
Semantic Embedding Vector
                │
                ▼
Cosine Similarity Computation
                │
                ▼
Repository Relationship Graph
```

The Hugging Face warning observed during execution:

```text
HF_TOKEN does not exist
```

does not indicate an error. It simply means the model is being downloaded anonymously rather than through an authenticated Hugging Face account. Since the model is publicly available, authentication is optional and does not affect the correctness of the project.

### Why Embeddings are Necessary

The generated embeddings enable the system to understand contextual meaning rather than relying solely on keyword overlap. Repositories discussing similar technologies, methodologies, or problem domains are mapped to nearby locations in the embedding space.

This semantic representation forms the foundation for:

* Repository similarity analysis
* Graph construction
* Community detection
* Developer recommendation

Without transformer embeddings, the graph would largely reflect keyword similarity rather than true conceptual relationships between repositories.

### Benefits of the Chosen Model

The **all-MiniLM-L6-v2** model was selected because it:

* Produces high-quality sentence embeddings
* Has low computational requirements
* Generates compact 384-dimensional vectors
* Provides fast inference suitable for large repository collections
* Achieves strong performance on semantic similarity tasks

As a result, the model offers an effective balance between accuracy and computational efficiency, making it well suited for large-scale GitHub repository analysis.

---
