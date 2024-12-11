# Evaluating the Effectiveness of Skip-Gram Based Item Embeddings in Recommendation Systems

## Project Structure

The project is organized into the following files and folders:

### 1. **Co-watcher Embeddings** (Co-watcher folder)
- **`Cowatcher_embedding.ipynb`**  
  This notebook generates item embeddings based on co-watcher data, which measures the similarity between items based on how often they are watched together. It utilizes the Skip-Gram model to create embeddings for each movie based on co-watching patterns.
  
- **`t-sne.ipynb`**  
  This notebook visualizes the co-watcher-based embeddings using t-SNE (t-distributed Stochastic Neighbor Embedding) to reduce dimensionality and explore the relationships between movies in the embedding space.

### 2. **Viewing Sequence Embeddings**
- **`viewing_sequence_embeddings.ipynb`**  
  This notebook generates embeddings based on the viewing sequences of users, capturing the temporal order in which movies are watched. These embeddings reflect how the sequence of user behavior can provide insights into item relationships, again utilizing the Skip-Gram approach.

### 3. **Tag and Genre Sharing Embeddings**
- **`tag_genre_sharing.ipynb`**  
  In this notebook, embeddings are generated by considering not only the movies but also their associated tags and genres. By incorporating these additional features, the model can capture a more comprehensive view of item relationships, which can help alleviate the cold-start problem in recommendation systems.

