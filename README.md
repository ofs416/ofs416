### Hi, I'm Oskar 👋

Machine learning engineer in London. Cambridge MEng (First-class) in Information, Control and Biological Engineering, with research in representation learning and particle filtering at Cambridge and UCL's Gatsby Unit.

I build ML systems where every output is verified and every model choice is a measurement.

- 🔨 **Now:** founder and ML engineer at **Questral**, generating exam-board-aligned maths questions with an agentic LLM + SymPy pipeline. Every question is proven correct in a sandbox and screened by a calibrated LLM-as-judge panel.
- 🔬 **Before:** research assistant at the [Gatsby Computational Neuroscience Unit](https://www.ucl.ac.uk/gatsby/), UCL, building inference pipelines for Recognition Parameterised Models in JAX and Julia.
- 📚 **Learning:** C++ and Rust, from the systems side down.

---

#### Selected projects

| Project | What it is | Stack |
|---|---|---|
| [**NN_API**](https://github.com/ofs416/NN_API) | Molecular solubility (logS) inference service from SMILES strings. A TorchScript model served by Ray Serve behind FastAPI on a multi-node Ray cluster with replica autoscaling, a Streamlit frontend, Locust load tests and CI. | PyTorch, Ray Serve, FastAPI, Pydantic, RDKit, Docker |
| [**DNA_LM**](https://github.com/ofs416/DNA_LM) | *In progress.* A BERT-style transformer, written from scratch, pre-trained on the human reference genome with masked and span-masked language modelling. Planned: FlashAttention, mixed precision, quantisation and distillation, and benchmarking on Genomic Benchmarks. | PyTorch, CUDA, W&B |
| [**e2eWebStream**](https://github.com/ofs416/e2eWebStream) | Real-time streaming pipeline with on-stream CNN inference: Airflow orchestration, Kafka transport, Spark Structured Streaming and Cassandra, all containerised. | Airflow, Kafka, Spark, Cassandra, Keras, Docker |
| [**cuda_kernels**](https://github.com/ofs416/cuda_kernels) | Hand-written CUDA C kernels with CPU baselines: GEMM with benchmarks, and convolution kernels iterated through tiling, shared memory and vectorised loads, used for MNIST classification. | C, CUDA |
| [**Python_Cuda_Abstractions**](https://github.com/ofs416/Python_Cuda_Abstractions) | The same GPU workload implemented in CuPy, custom CuPy kernels, Numba, Triton and Taichi, to measure the performance vs. ease-of-use trade-off of each abstraction level. | CuPy, Numba, Triton, Taichi |
| [**Reinforcement_Learning**](https://github.com/ofs416/Reinforcement_Learning) | From optimal and model-predictive control through MDPs to tabular Q-learning and deep RL, with a configurable FrozenLake environment. | Python, Gymnasium |
| [**SGEMM**](https://github.com/ofs416/SGEMM) | *In progress.* A single-precision GEMM in modern C++, starting from a templated matrix class with tests. | C++, CMake |

#### Probabilistic modelling (Cambridge coursework)

- [**Bayesian_Julia**](https://github.com/ofs416/Bayesian_Julia): variational Bayesian neural network in Julia (Pluto, Zygote)
- [**Graph_Models**](https://github.com/ofs416/Graph_Models): TrueSkill-style player skill ranking on tennis match data
- [**Brain_Machine_Interfaces**](https://github.com/ofs416/Brain_Machine_Interfaces): neural decoding with Wiener and Kalman filters
- [**Probabilistic_Machine_Learning**](https://github.com/ofs416/Probabilistic_Machine_Learning) and [**Bayesian_Inference**](https://github.com/ofs416/Bayesian_Inference): Bayesian logistic classification with the Laplace approximation
- [**Practical_Optimisation**](https://github.com/ofs416/Practical_Optimisation): genetic algorithms and a hybrid GA–PSO in Julia

---

#### Toolbox

**Languages:** Python · Julia · C++ · SQL · C/CUDA · learning Rust  
**ML:** PyTorch · JAX · Flux.jl · RxInfer.jl · scikit-learn · NumPy · Pandas  
**Systems:** Docker · Ray · FastAPI · Pydantic · LiteLLM · PostgreSQL/pgvector · Kafka · Airflow · GCP · CI/CD · W&B · Pytest

#### Get in touch

[LinkedIn](https://linkedin.com/in/oskar-stone) · [oskarfstone@gmail.com](mailto:oskarfstone@gmail.com)
