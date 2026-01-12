# IBM-RAG

# Tokenization
Every journey begins with breaking text into digestible pieces called tokens. The sentence “Hello world” becomes separate tokens that the model can process. Using techniques like Byte Pair Encoding, common letter combinations become single tokens, while rare words get split apart. Each token gets assigned a unique number, transforming human language into mathematical data the model can understand.<BR>

If you’d like to take a closer look at how different language models perform tokenization, you can play around with Tiktokenizer, an online tool built by David Duong that’s designed for visualizing tokenized text input!<BR>


**Tool to visulize token** <BR>
Tiktokenizer(https://tiktokenizer.vercel.app/?model=gpt-4-1106-preview)

# Embeddings
These token numbers are then transformed into vectors - lists of hundreds of decimal numbers that capture meaning in mathematical space. Words with similar meanings cluster together in this high-dimensional space, like “cat” and “dog” being closer than “cat” and “airplane.”<BR>

To understand how embeddings group information, explore the Nomic Atlas map linked below. Every dot you see is an embedding of a Wikipedia biography and the coloured clusters reveal underlying connections between people across history.<BR><BR>
**Tool to visulize embeddings**<BR>
https://atlas.nomic.ai/data/nomic/wiki-people/map

# Transformer Layers
These attention mechanisms stack into layers. Information flows upward through dozens of layers, with each one building more sophisticated representations. Early layers might focus on basic grammar and word relationships, while deeper layers develop complex reasoning abilities and factual knowledge. To keep this flow stable, the model also passes forward the original input of each layer alongside the new transformations. This helps preserve important details and prevents information from being lost or distorted as it moves through many layers.<BR>
<BR>
**Tool to visualize LLM** <BR>
https://bbycroft.net/llm
