## TinyModel-15M
How small can a language model be and still generate coherent english?
TinyModel is a 15-million parameter language model built from the ground up to explore the limits of extreme compression in natural language understanding. While modern LLMs brag about billions of parameters, this project focuses on the opposite: achieving coherent, grammatical English in a package small enough to run on a toaster.

🚀 The Mission
The goal was to see if a model with only 15M parameters could master the simplified vocabulary and narrative structures of the TinyStories dataset.
The Verdict: It works. By focusing on high-quality, synthetic children's stories, the model captures grammar, basic logic, and narrative flow without the "bloat" of a general-purpose LLM.

🛠️ Built From Scratch
This isn't a fine-tuned version of someone else's model. Everything here was coded from zero:

* Architecture: Standard Transformer (Decoder-only).
* Parameters: ~15 Million.
* Dataset: TinyStories (Instruction/Story pairs).

🧠 What I Learned

* Data Quality > Model Size: Small models are incredibly sensitive to noise. The purity of the TinyStories dataset is what makes 15M parameters viable.
* Optimization: Every parameter counts. Adjusting the head dimension and learning rate schedule had outsized impacts compared to larger models.


