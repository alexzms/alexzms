### Hi, I'm Minshen Zhang 👋

[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/alexzms)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/minshen-zhang-416a0b291/)
[![Personal Website](https://img.shields.io/badge/-Website-47CCCC?style=flat&logo=Google-Chrome&logoColor=white)](https://alexzms.github.io)
[![Gmail](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:alexzhangminshen@gmail.com)

I am an M.S. student in Computer Science at **UC San Diego**, advised by [Prof. Hao Zhang](https://cseweb.ucsd.edu/~haozhang/) in **[Hao AI Lab](https://haoailab.com/)**. I worked as a **Student Researcher Intern at ByteDance Seed Infra**. I hold a B.S. from **ShanghaiTech University**, where I was advised by [Prof. Kewei Tu](https://scholar.google.com/citations?user=5gi3Pm0AAAAJ&hl=en).

I work on **efficient AI systems**: LLM serving, GPU/TPU kernel optimization, sparse attention, and agents for performance engineering. I enjoy connecting model architecture, on-chip dataflow, and distributed execution to make models more efficient in practice.

#### Current work

- **[FastAFD](https://haoailab.com/blogs/fastafd/)** — Currently contributing to a new inference engine project focused on **LLM inference optimization**.
- **AutoPallas at ByteDance** — During my internship, I was code owner of an internal agent system for TPU kernel optimization, with interactive task specification, configurable single-/multi-agent loops, parallel optimization exploration, a strict correctness gate, and reusable optimization trajectories. I also optimized Pallas paged-attention and fused kernels, using HLO/LLO analysis and XProf profiling with XLA as a performance baseline.

#### Research and open source

- **[HiLS-Attention](https://arxiv.org/abs/2607.02980)** — Core contributor; built the official **SGLang serving backend** and reference inference system for learned sparse attention, supporting **512K-token context**.
- **[FlashMHF / FlashFFN](https://arxiv.org/abs/2512.06989)** — First-author research on software–hardware co-design for efficient FFN architectures. I wrote Flash-style kernels in **ThunderKittens/CUDA and Triton** that keep intermediates in SRAM. The project reduces peak memory by **3–5×** and achieves up to **1.08×** inference speedup over the SwiGLU baseline while improving model quality.
- **[FastVideo](https://github.com/hao-ai-lab/FastVideo)** — **One of the code owners**, contributing training infrastructure, custom GPU kernels, inference optimization, and quantization-aware distillation for video generation and world models.

---
**Technical focus:** `LLM Serving` `GPU/TPU Kernels` `Coding Agents` `Sparse Attention` `Software–Hardware Co-design`
