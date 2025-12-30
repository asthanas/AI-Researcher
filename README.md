# 🧠 AI Researcher Roadmap (Beginner → Advanced)

> **Duration:** 365 Days (12 Months)  
> **Target Audience:** Absolute beginners to AI who want to reach **research-level expertise**  
> **Outcome:** Research-ready AI engineer capable of reading, reproducing, and publishing papers

---

## 🎯 What You Will Achieve
By following this roadmap completely, you will:

- Build **strong math foundations** (linear algebra, probability, optimization)
- Understand **machine learning from first principles**
- Master **deep learning architectures and training**
- Learn **research methodology** used in top labs
- Reproduce **state-of-the-art research papers**
- Produce **one original research project or paper**

---

## ⏱️ Daily Time Commitment
**3.5 – 5 hours/day**

| Activity | Time |
|------|------|
| Math & theory | 1.5 hrs |
| Coding & experiments | 1.5 hrs |
| Paper reading | 45 mins |
| Notes & writing | 30 mins |

---

# 🔰 LEVEL 0 — Foundations (Day 1–30)
**Goal:** Become comfortable with math and Python required for ML

---

## 📘 Linear Algebra

**Direct Learning Links**
- MIT 18.06 (Gilbert Strang – full course): https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/
- 3Blue1Brown – Essence of Linear Algebra: https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr
- Linear Algebra Done Right (book): https://linearalgebradonewrong.com/

**Coding Assignments**
- Implement vector & matrix operations using NumPy
- PCA from scratch (no sklearn)

**Topics**
- Scalars, vectors, matrices
- Dot product, norms
- Linear independence
- Rank, null space
- Eigenvalues & eigenvectors
- Singular Value Decomposition (SVD)
- Projections & orthonormal bases

**Resources**
- MIT 18.06 – Gilbert Strang
- *Linear Algebra Done Right* – Sheldon Axler
- 3Blue1Brown (YouTube)

**Deliverables**
- Derive PCA using SVD
- Implement matrix operations from scratch in Python

---

## 📘 Probability & Statistics

**Direct Learning Links**
- Khan Academy – Probability & Statistics: https://www.khanacademy.org/math/statistics-probability
- StatQuest (Josh Starmer): https://www.youtube.com/@statquest
- PRML (Bishop) companion resources: https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/

**Coding Assignments**
- Simulate coin tosses & dice rolls
- Visualize LLN & CLT using Python

**Topics**
- Probability axioms
- Conditional probability
- Bayes theorem
- Random variables
- Expectation & variance
- Common distributions
- Law of Large Numbers
- Central Limit Theorem

**Resources**
- Khan Academy
- StatQuest
- Bishop – PRML (Ch 1–2)

**Deliverables**
- Simulate distributions in Python
- Visualize convergence of LLN & CLT

---

## 💻 Python for Research

**Direct Learning Links**
- NumPy official tutorials: https://numpy.org/learn/
- PyTorch official tutorials: https://pytorch.org/tutorials/
- Matplotlib gallery: https://matplotlib.org/stable/gallery/index.html

**Coding Assignments**
- Implement Gradient Descent for linear regression
- Plot loss vs iterations

**Topics**
- NumPy internals
- Broadcasting & vectorization
- Matplotlib & Seaborn
- PyTorch tensors & autograd

**Deliverables**
- Implement Gradient Descent
- Plot loss curves

---

# ⚙️ LEVEL 1 — Classical Machine Learning (Day 31–90)
**Goal:** Understand *why* ML algorithms work

---

## 📘 Algorithms

**Direct Learning Links**
- Elements of Statistical Learning (free PDF): https://hastie.su.domains/ElemStatLearn/
- Andrew Ng ML Course: https://www.coursera.org/learn/machine-learning
- PRML lecture notes: https://www.cs.ubc.ca/~murphyk/Teaching/CS340-Fall06/

**Coding Assignments**
- Implement Logistic Regression from scratch
- Implement kNN & SVM without sklearn

- Linear Regression (normal equation + GD)
- Logistic Regression
- k-Nearest Neighbors
- Naive Bayes
- Support Vector Machines (primal & dual)
- Decision Trees
- Random Forests
- Boosting
- EM Algorithm

**Resources**
- *Elements of Statistical Learning* – Hastie et al.
- Bishop – PRML
- Andrew Ng ML Course

---

## 📐 Mathematical Concepts
- Convex optimization
- Lagrange multipliers
- Bias–variance tradeoff
- Loss surfaces

---

## 🧪 Experiments
- Compare classifiers under noise
- Feature scaling experiments
- Overfitting vs underfitting studies

---

## 📖 Paper Reading (Start Here)

**Foundational Papers (Direct Links)**
- Perceptron (Rosenblatt, 1958): https://psycnet.apa.org/record/1959-09865-001
- SVM (Cortes & Vapnik): https://link.springer.com/article/10.1007/BF00994018
- Random Forests (Breiman): https://www.stat.berkeley.edu/~breiman/randomforest2001.pdf

**Assignment**
- Write a 1-page summary covering problem, method, assumptions, limitations

**1 paper/week**
- Perceptron
- SVM
- Random Forests

**Deliverable**
- 1-page structured paper summary

---

# 🧠 LEVEL 2 — Deep Learning Core (Day 91–180)
**Goal:** Understand neural networks from equations to code

---

## 📘 Fundamentals

**Direct Learning Links**
- Deep Learning Book (Goodfellow): https://www.deeplearningbook.org/
- CS231n notes: https://cs231n.stanford.edu/
- MIT 6.S191 videos: https://introtodeeplearning.com/

**Coding Assignments**
- Implement backpropagation for MLP from scratch
- Compare SGD vs Adam

- Backpropagation (full derivation)
- Chain rule (vector form)
- Activation functions
- Weight initialization
- Optimization methods
- Learning rate schedules
- Regularization

**Resources**
- *Deep Learning* – Goodfellow et al.
- CS231n (Stanford)
- MIT 6.S191

---

## 🧠 Architectures

**Direct Learning Links**
- CNNs (CS231n): https://cs231n.github.io/convolutional-networks/
- RNNs & LSTMs: https://colah.github.io/posts/2015-08-Understanding-LSTMs/
- Attention & Transformers: https://jalammar.github.io/illustrated-transformer/

**Coding Assignments**
- Train CNN on CIFAR-10: https://www.cs.toronto.edu/~kriz/cifar.html
- Implement scaled dot-product attention

- Multi-Layer Perceptrons
- Convolutional Neural Networks
- RNN, LSTM, GRU
- Attention mechanism
- Transformers (deep dive)

---

## 🧪 Hands-on Work
- Build a neural network framework from scratch
- Implement backprop manually
- Train CNN on CIFAR-10
- Implement attention layer manually

---

## 📖 Paper Reading
**2 papers/week**
- AlexNet
- ResNet
- Transformer

---

# 🧪 LEVEL 3 — Research Engineering (Day 181–270)
**Goal:** Think and work like a researcher

---

## 🔬 Research Skills
- Hypothesis formulation
- Controlled experiments
- Ablation studies
- Failure analysis
- Reproducibility

---

## 📘 Advanced Topics
- Optimization landscapes
- Generalization theory
- Double descent
- Overparameterization
- Initialization theory

---

## 🧪 Paper Reproduction (Mandatory)

**Direct Paper Links**
- Adam Optimizer: https://arxiv.org/abs/1412.6980
- ResNet: https://arxiv.org/abs/1512.03385
- Transformer: https://arxiv.org/abs/1706.03762

**Reproduction Resources**
- Papers With Code: https://paperswithcode.com/

Reproduce at least:
- Adam Optimizer
- ResNet
- Transformer (simplified)

---

## 🧠 Reading Strategy
**3 papers/week**
1. Foundational paper
2. Recent paper (≤ 2 years)
3. Negative results / analysis paper

---

## 🛠 Tools to Learn
- Weights & Biases
- Hydra configs
- MLflow
- Docker

---

# 🎯 LEVEL 4 — Specialization (Day 271–330)
**Goal:** Achieve depth in ONE research area

---

## Choose One Track

### 🔹 Reinforcement Learning

**Learning Links**
- Sutton & Barto book: http://incompleteideas.net/book/the-book-2nd.html
- OpenAI Spinning Up: https://spinningup.openai.com/en/latest/

**Datasets & Environments**
- OpenAI Gym: https://www.gymlibrary.dev/
- D4RL Offline RL datasets: https://github.com/Farama-Foundation/D4RL

- Markov Decision Processes
- Policy gradients
- PPO, SAC
- Offline RL
- Decision Transformers

**Resources**
- Sutton & Barto
- OpenAI Spinning Up

---

### 🔹 Probabilistic Machine Learning

**Learning Links**
- Murphy – Probabilistic ML: https://probml.github.io/pml-book/
- Variational Inference tutorial: https://arxiv.org/abs/1601.00670

**Datasets**
- UCI ML Repository: https://archive.ics.uci.edu/ml/index.php

- Bayesian inference
- Variational inference
- Gaussian Processes
- Uncertainty estimation

**Resources**
- Murphy – Probabilistic ML
- Bishop – Advanced PRML

---

### 🔹 NLP / LLMs

**Learning Links**
- Hugging Face NLP Course: https://huggingface.co/course
- Illustrated GPT: https://jalammar.github.io/illustrated-gpt2/

**Datasets**
- GLUE benchmark: https://gluebenchmark.com/
- WikiText: https://paperswithcode.com/dataset/wikitext-103

- Language modeling
- Scaling laws
- Fine-tuning
- RAG systems
- Alignment basics

---

### 🔹 Computer Vision

**Learning Links**
- Self-Supervised Learning survey: https://arxiv.org/abs/2006.08218
- Vision Transformers: https://arxiv.org/abs/2010.11929

**Datasets**
- ImageNet: https://www.image-net.org/
- COCO: https://cocodataset.org/

- Self-supervised learning
- Contrastive learning
- Vision Transformers

---

## 🧪 Capstone Project
- Define a research question
- Establish baselines
- Propose improvements
- Evaluate with proper metrics

---

# 📝 LEVEL 5 — Publishing & Research Identity (Day 331–365)
**Goal:** Become a visible, credible AI researcher

---

## 📝 Write a Research Paper
- Follow NeurIPS / ICML format
- Clearly state contributions
- Include honest limitations

**Resource**
- *How to Write a Great Research Paper* – Simon Peyton Jones

---

## 🌍 Publish & Share
- arXiv preprint
- GitHub repository
- Blog post explaining intuition
- LinkedIn / Twitter research thread

---

# 📅 Weekly Paper-Reading Schedule (52 Weeks)

Follow this schedule alongside the roadmap. Aim for **2 papers/week after Month 3**.

---

## Weeks 1–4: Foundations of Learning
- Rosenblatt (1958): *The Perceptron*
- Cover & Hart (1967): *Nearest Neighbor Pattern Classification*
- Bishop (overview): Probabilistic ML foundations

Goal: Understand what "learning" means mathematically.

---

## Weeks 5–8: Classical ML Theory
- Vapnik: *Statistical Learning Theory (overview)*
- Cortes & Vapnik: *Support Vector Machines*
- Breiman: *Random Forests*

Goal: Bias–variance, margins, ensemble intuition.

---

## Weeks 9–12: Optimization & Generalization
- Bottou: *Stochastic Gradient Descent Tricks*
- Nesterov: *Introductory Lectures on Convex Optimization*
- Goodfellow: Optimization chapter (DL book)

Goal: Why gradient descent works.

---

## Weeks 13–16: Neural Networks Foundations
- Rumelhart et al. (1986): *Backpropagation*
- Cybenko (1989): *Universal Approximation Theorem*
- Glorot & Bengio: Initialization

Goal: Why neural networks are expressive.

---

## Weeks 17–20: CNNs & Vision Breakthroughs
- LeCun (1998): *LeNet*
- Krizhevsky (2012): *AlexNet*
- He et al. (2015): *ResNet*

Goal: Representation learning in vision.

---

## Weeks 21–24: Sequence Models
- Elman RNNs
- Hochreiter & Schmidhuber: *LSTM*
- Cho et al.: *GRU*

Goal: Temporal modeling.

---

## Weeks 25–28: Attention & Transformers
- Bahdanau et al.: *Attention*
- Vaswani et al.: *Attention Is All You Need*
- Transformer analysis papers

Goal: Modern sequence modeling.

---

## Weeks 29–32: Regularization & Generalization
- Dropout (Srivastava)
- BatchNorm (Ioffe & Szegedy)
- Double Descent (Belkin)

Goal: Why big models generalize.

---

## Weeks 33–36: Representation & Self-Supervised Learning
- Autoencoders
- SimCLR
- MoCo

Goal: Learning without labels.

---

## Weeks 37–40: Probabilistic ML
- Variational Autoencoders
- Bayesian Neural Networks
- Gaussian Processes

Goal: Uncertainty-aware learning.

---

## Weeks 41–44: Reinforcement Learning
- Sutton & Barto (core chapters)
- DQN
- PPO

Goal: Sequential decision-making.

---

## Weeks 45–48: Modern Research Directions
- Scaling Laws
- Foundation Models
- Alignment basics

Goal: Research trends.

---

## Weeks 49–52: Your Specialization
- Read 6–10 papers only in your chosen area
- Mix foundational + recent work

Goal: Prepare for publication or interviews.

---

# ✅ Final Checklist
- [ ] Strong math foundations
- [ ] Classical ML mastery
- [ ] Deep learning expertise
- [ ] 5–10 reproduced papers
- [ ] 1 specialization
- [ ] 1 original research project or paper

---

## 📄 Paper Reading Template

Use this template **for every paper you read**. Store one Markdown file per paper.

```
# Paper Title

## 1. Citation
- Authors:
- Conference / Journal / Year:
- Paper link:
- Code link (if any):

## 2. Problem Statement
- What exact problem is this paper solving?
- Why is this problem important?

## 3. Key Idea (High-Level Intuition)
- Explain the core idea in simple words
- What is new compared to prior work?

## 4. Method / Algorithm
- Model architecture / pipeline
- Mathematical formulation (key equations)
- Assumptions made

## 5. Experiments
- Datasets used
- Baselines compared
- Evaluation metrics

## 6. Results
- Main quantitative results
- Where does it win / lose?

## 7. Strengths
- What does this paper do really well?

## 8. Weaknesses / Limitations
- Where does it fail?
- Unrealistic assumptions?

## 9. Reproducibility Notes
- Missing details?
- Hyperparameters unclear?

## 10. Ideas & Extensions
- How can this be improved?
- Can this idea be applied elsewhere?

## 11. One-Sentence Summary
> If I had to explain this paper to someone in one sentence:
```

---

## 🧪 Experiment Log Template

Use this template **for every experiment you run** (even failed ones).

```
# Experiment Title

## 1. Date & Experiment ID
- Date:
- Experiment ID / Run name:

## 2. Research Question / Hypothesis
- What am I trying to test or prove?

## 3. Setup
- Model architecture:
- Dataset:
- Train/validation split:
- Hardware:

## 4. Hyperparameters
| Parameter | Value |
|---------|-------|
| Learning rate | |
| Batch size | |
| Optimizer | |
| Epochs | |

## 5. Baseline
- What is the baseline model?
- Baseline performance:

## 6. Changes Introduced
- What did I change compared to baseline?

## 7. Metrics & Results
| Metric | Value |
|-------|------|

## 8. Observations
- Training stability
- Convergence behavior
- Unexpected behavior

## 9. Failure Analysis
- What didn’t work?
- Why might it have failed?

## 10. Conclusion
- Did the hypothesis hold?

## 11. Next Steps
- What should be tried next?
```

---

## 🧠 Research Mindset Rules
- Derive before coding
- Read papers slowly
- Question assumptions
- Fail and learn publicly

---

🚀 **Follow this roadmap with discipline and curiosity, and you will transition from beginner to advanced AI researcher within one year.**

