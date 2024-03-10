# ai-paper-stream
a stream of interesting papers read or to be read

---
1. **[The Era of 1-bit LLMs: All Large Language Models are in 1.58 Bits](https://arxiv.org/abs/2402.17764):** LLM is ternary {-1, 0, 1}, BitNet b 1.58. Resource use and performance benefits. Could open up new avenues for arch design
   
2. **[Orca 2: Teaching Small Language Models How to Reason](https://arxiv.org/pdf/2311.11045.pdf):** still fun to plug the questions into newer models. E.g. Mistral large, which just cruises through them.

3. **[Triton: An Intermediate Language and Compiler for Tiled Neural Network Computations](http://www.eecs.harvard.edu/~htk/publication/2019-mapl-tillet-kung-cox.pdf):** THE original Triton paper. So modest. But all your base is belong to us. One script to rule them all, and in the tensor to bind them. https://github.com/openai/triton https://triton-lang.org/main/index.html

4. **[The Cache Performance and Optimizations of Blocked Algorithms](https://suif.stanford.edu/papers/lam-asplos91.pdf):** Comprehensive study of blocking algorithms and how they can take advantage of memory hierarchies. Referenced in the Triton literature

5. **[FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning](https://tridao.me/publications/flash2/flash2.pdf):** The Attention layers scale *quadratically* in compute and memory with context length. Tri Dao's work improves this by rescheduling with better work partitioning to get device util up to ~70%. Has been implemented in Triton.

6. **[Ternary optical computer principle](https://www.researchgate.net/publication/220362922_Ternary_optical_computer_principle):** 3 states of light (horizontal & vertical polarization and off) are used in this proposal for a ternary computer (with all the advantages that ternary logic provides over binary https://en.wikipedia.org/wiki/Balanced_ternary). Read in conjuction with 1.

7. **[Hegel 2.0 The imaginary history of ternary computing](https://www.cabinetmagazine.org/issues/65/weatherby.php):** Amusing article in *Cabinet*

8. **[The Sky Above The Clouds](https://arxiv.org/pdf/2205.07147.pdf):** beyond cloud computing with intercloud brokers - an imagination of the evolution of cloud computing
