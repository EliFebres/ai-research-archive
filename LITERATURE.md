These papers are in the order that I read them.


## 01 A Few Useful Things to Know About Machine Learning [pdf](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)
Pedro Domingos

Machine learning succeeds when models generalize, not when they memorize. This essay distills practice-tested lessons: data representation and quality often matter more than algorithm choice (“more data beats clever algorithms”); overfitting is the primary failure mode, mitigated by regularization, cross-validation, and honest holdouts; useful models navigate the bias–variance trade-off rather than “solving” it; there is no universally best learner (No Free Lunch), so methods must match problems and assumptions; features carry most of the signal, but leakage and target bleed can silently poison results; ensembles frequently improve robustness; nonstationarity and feedback loops break i.i.d. assumptions; correlation is not causation; and evaluation must mirror deployment with the right metrics and baselines. Together, these rules of thumb form a compact field guide for building models that perform reliably in the wild.


## 02 The Bitter Lesson [pdf] (https://www.cs.utexas.edu/~eunsol/courses/data/bitter_lesson.pdf)
Rich Sutton

The biggest advances in AI have come from general methods that exploit computation—search, learning, and planning—rather than from hand-crafted domain knowledge. Across chess and Go to speech and vision, human-encoded structure offers short-term gains but doesn’t scale with Moore’s law; compute-hungry, general-purpose learners do. The “bitter lesson” is to build agents that let learning and search acquire the knowledge—via reinforcement learning, optimization, and even meta-learning—while avoiding domain-specific tricks that cap performance. As data and compute grow, such methods keep improving; knowledge-heavy systems stagnate.