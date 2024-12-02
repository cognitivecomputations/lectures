# Attention Lectures

## Attention Fundamentals
- Brief historical context (5 min)
  - Evolution: FFN → RNN → LSTM → Attention
  - Why direct connections matter
- Query/Key/Value framework
- Dot-product attention mathematics
- Softmax and scaling deep dive
- Worked example from start to finish
- Attention pattern visualization
- Masking in attention

## Multi-Head Attention
- Why single attention head isn't enough
- Parameter matrices breakdown
- Linear projections in detail
- Head dimension calculations
- Pattern specialization per head
- Output aggregation mechanisms
- Parallel computation benefits

## Rotary Positional Embeddings
- Absolute vs relative positioning
- RoPE mathematics
- Implementation details
- Benefits over other positional approaches
- Scaling considerations

## The Context Length Challenge
- Quadratic scaling problem
- Memory and computation bounds
- Needle in haystack experiments
- Key metrics for long context
- Path from 2K to 100K+ tokens
- Current SOTA approaches
- Real-world implications

## KV Cache
- Core KV caching concept
- Memory savings mathematics
- Implementation deep dive
- Autoregressive generation patterns
- Common pitfalls and solutions
- Performance implications

## Flash Attention
- IO-aware attention computation
- Tiling strategies
- Memory hierarchy optimization
- Implementation details
- Flash Attention 1 vs 2
- Performance gains

## Sliding Window & Sparse Attention
- Local vs global attention patterns
- Sparse attention matrices
- Block-sparse implementations
- Longformer/BigBird approaches
- Trade-offs in long sequences

## Grouped Query Attention
- Memory scaling problems in attention
- GQA mathematical foundation
- Head grouping strategies
- Memory vs performance tradeoffs
- Implementation considerations
- Real-world benchmarks

## Multi-head Latent Attention
- Latent space fundamentals
- Dimensionality reduction mathematics
- Query/key space transformations
- Computational efficiency gains
- Implementation challenges
- Practical considerations

## Linear/State Space Attention
- Linear attention mechanisms
- State space models
- Mamba architecture insights
- Performance characteristics
- When to use linear alternatives

## Differential Attention
- Attention noise problem
- Dual softmax mechanism in detail
- Lambda parameter dynamics
- GroupNorm's role
- Training considerations
- Performance characteristics
- Empirical improvements

## Mixture of Experts Attention
- MoE fundamentals
- Expert routing in attention
- Balancing and gating
- Training considerations
- Scaling properties
