# Workshops and Tutorials

ICPP 2026 will host co-located workshops and tutorials on the first day of the conference, **September 28, 2026**.

## Workshops

Details for each workshop, including calls for papers and submission instructions, are maintained on the workshop websites.

**[International Workshop on Data Compression for AI and Big Data Applications (DC4AI)](https://hpc-and-ai.github.io/DC4AI-2026/){:target="_blank"}**

**[State of Practice in Deploying Supercomputers with NVIDIA Superchips (SPIN-NVSC / NVSUG)](https://nvsug.github.io/spin-nvsc/){:target="_blank"}**

**[Benchmarking in the Data Center (BID)](https://parallel.computer/){:target="_blank"}**

**[Sustainable Computing for High-Performance and Distributed Systems (SUSTAIN-HPC)](https://icpp2026.github.io/sustain-hpc-2026/){:target="_blank"}**

**[Agentic AI in Real-World Systems: Infrastructure, Algorithms, and Deployment (non-archival)](https://airs-workshop.github.io/){:target="_blank"}**

!!! note

    Additional workshops will be listed here as they are announced. For information on proposing a workshop, see the [Call for Workshops](call-for-workshops.md).

----

## Tutorials

### **Accelerating AI and HPC Workflows with AMD ROCm AI and Modern GPU Clusters**

**Presenters:**

- Kerwin Tsai (AMD)
- Haris Javaid (AMD) (tentative)

**Abstract:** This tutorial introduces AMD's latest AI and HPC ecosystem, focusing on ROCm AI, large-scale GPU cluster deployment, and practical experiences from real-world AI/HPC systems. Participants will learn how to develop, optimize, and deploy AI and HPC workloads on AMD Instinct GPUs using the ROCm software stack. The tutorial combines technical presentations with hands-on demonstrations and best practices from production cluster environments.

**Target Audience:** Researchers, HPC practitioners, AI engineers, and graduate students.

**Learning Objectives:** After the tutorial, participants will be able to:

- AMD Research opportunities
- Understand the ROCm software ecosystem
- Run workloads on AMD GPUs in agentic way

**Agenda (Half-Day, ~3 hours):**

- **Session 1: AMD AI & HPC Ecosystem (45 min)**
    - Introduce to AMD University Program
    - Introduce to AMD AI & HPC Cluster Program
- **Session 2: ROCm.AI (45 min)**
    - Overview of ROCm.AI
    - ROCm.AI Quick Demo
- **Break-time (10 min)**
- **Session 3: AMD Research sharing (60 min)**
    - AI in DC
    - Physical AI
- **Session 4: Experience Sharing (30 min)**
    - Mars Computing (@Prof. He, 15 min)

**Reference:** [Tutorial overview (PDF)](assets/tutorials/icpp2026-tutorial-amd-rocm-ai.pdf){:target="_blank"}

----

### **Coyote V2: An Open-Source FPGA Shell for Modern Distributed Data Processing**

**Presenter:** Dr. **Shien Zhu**, Systems Group, ETH Zurich, Switzerland — [shien.zhu@inf.ethz.ch](mailto:shien.zhu@inf.ethz.ch)

**Introduction:** FPGAs have proven to be excellent prototyping platforms for next-generation systems thanks to their stream-like nature and configurability. However, practically integrating them into realistic systems remains challenging.

In this 3-hour tutorial, we introduce Coyote V2, an open-source infrastructure for implementing SmartNICs on FPGAs as highly versatile, network-enabled acceleration platforms. Coyote V2 provides abstractions of FPGA resources and RDMA interfaces for in-network processing and advanced network management, in addition to DPU-like local acceleration. We will introduce our infrastructure and showcase how its high-level abstractions benefit the FPGA deployment, including accelerating quantized models from Python, offloading various functions (encryption, compression, recommender model pre-processing) to the network datapath, and distributed database transaction processing.

**Learning Objectives:** Attendees will achieve the following learning objectives:

- List the benefits of FPGA abstraction with shells
- Know the architecture and interfaces of Coyote V2
- Build customized FPGA applications with Coyote V2

Additional learning objectives:

- Integrate high-level programming languages like SpinalHDL/Scala and Python with Coyote V2
- Automate the application deployment workflow

**Outline:** This tutorial will take ~3 hours. The schedule is as follows:

- **10-minute Introduction**: Presenting an overview of recent cloud and data center trends, hardware specialization and infrastructure for the AI/ML era. We will also introduce the external page AMD Heterogeneous Accelerated Compute Cluster (HACC) at ETH Zurich as a platform to support research in computer systems, architecture and networking.
- **50-minute Coyote V2**: Presenting Coyote V2 basics and interfaces. Showing how to seamlessly deploy an accelerated application on an FPGA in a few lines of C++. Additionally, examples and live demos of hybrid computer systems with FPGAs and GPUs will be presented.
- **15-minute Q/A**
- **30-minute Network Applications**: Giving an overview and live demo of our RDMA stack, RoCE BALBOA. It will showcase how to perform 100G RDMA networking in a few lines of C++ code between two FPGAs as well as a FPGA and a commodity NIC (Mellanox-5).
- **30-minute AI Applications**: Showcasing how to use FPGA-based SmartNICs to deploy ML pre-processing onto the network datapath and deploy low-latency quantized neural networks by utilizing the memory interfaces.
- **30-minute Database Applications**: Presenting another example on FPGA-based distributed transaction processing with Coyote V2. It features efficient development with SpinalHDL and simulation-based design space exploration.
- **15-minute Q/A**

**Acknowledgment:** This work was supported in part by AMD and ETH Zurich, who provided access to the Heterogeneous Accelerated Compute Cluster (HACC) at ETHZ.

**Reference:** [Tutorial overview (PDF)](assets/tutorials/icpp2026-tutorial-coyote-v2.pdf){:target="_blank"}
