# Michal Hornicky

<img src="photo.jpg" alt="Profile Photo" width="150" style="float: right; margin: 0 0 10px 10px;">

**Software Engineer | AI Engineer | Distributed Systems Engineer**

📍 Zurich, Switzerland  
📧 semtexzv@gmail.com  
📱 +41 79 810 28 94  
🔗 [github.com/semtexzv](https://github.com/semtexzv)  

---

## About Me

Highly skilled and experienced software engineer with a proven track record of success in developing and deploying high-performance, scalable applications. Expertise in a wide range of technologies, including machine learning, distributed systems, and cloud computing. Passionate about solving complex problems and delivering value.

---

## Skills

### Technical Expertise
- **LLMs & AI**: Multi-agent systems, autonomous agents, model integration, prompt engineering
- **Machine Learning Infrastructure**: Distributed training, inference optimization, autodiff frameworks
- **Distributed Systems**: High-performance services, event-driven architectures, microservices
- **Cloud Computing**: Kubernetes, Azure, cloud-native applications
- **Mobile Applications**: Android, iOS, cross-platform development
- **GPGPU Programming**: CUDA, OpenCL, performance optimization

### Programming Languages
- **Expert**: Rust, Go
- **Proficient**: Python, Kotlin, Java
- **Experienced**: C++, C, JavaScript (React)

### Spoken Languages
- Slovak (Native)
- Czech (Native)
- English (Fluent)

---

## Work Experience

### Software Engineer - Google DeepMind
**Zurich | November 2024 - Current**
- Led infrastructure efforts for Gemini application testing, designing QA processes and supporting technologies
- Led integration of AI Agents into testing workflows, improving automation and efficiency
- Implemented features directly in the Gemini application, contributing to core product development
- Conducted extensive research on various AI agent architectures and capabilities
- Organized knowledge-sharing workshops and mentored team members on AI agent architectures and best practices

### Software Engineer - Google
**Zurich | November 2021 - November 2024**
- Developed tooling, internal processes, automated testing architecture for Android and iOS Applications
- Supported testing & releases for Google Assistant, Google Search Application, and Gemini/Bard mobile applications
- Led efforts for using LLMs for automated testing & software verification

### Senior Software Engineer - RedHat
**Brno | July 2020 - September 2021**
- Led the server development team for the Patch application on cloud.redhat.com
- Scaled the patch application to serve thousands of large-scale deployments per day
- Moved update management for fleets of RHEL deployments to the Cloud
- Supported other teams with developing and deploying their applications on the same platform

### Software Engineer - RedHat
**Brno | September 2019 - July 2020**
- Ensured performance of the Vulnerability application on cloud.redhat.com
- Initiated the development of the Patch application on the same platform
- Developed libraries and tools for integrating Go language into a pre-existing Python-based ecosystem

### Android Developer - TouchArt s.r.o
**Brno | March 2016 - September 2019**
- Managed all aspects of several Android applications, from initial research, customer communication, development, testing, and deployment
- Led architectural overhauls, migration to Kotlin, usage of MVVM and reactive dataflow paradigms
- Directly contributed to more than 10 mobile applications developed for other companies

---

## Education

### Master's Degree - Information Technology
**Brno University of Technology | 2017-2019**

### Bachelor's Degree - Information Technology
**Brno University of Technology | 2014-2017**

---

## Notable Projects

### [GenAgent](https://github.com/semtexzv/genagent) - AI-Powered Multi-Agent Assistant (Experimental)
Experimental macOS/iOS taskbar AI assistant with multi-agent capabilities
- **Multi-agent system** supporting concurrent task execution across different domains
- **Multi-provider support**: OpenAI, Anthropic Claude, Google Gemini, Groq, Cohere, Ollama
- **Tool-augmented agents**: File operations, command execution, git integration, web search
- **Voice capabilities**: Deepgram transcription and OpenAI text-to-speech
- **Architecture**: Rust backend with tokio async runtime, Swift frontend with SwiftUI
- **Cross-platform FFI bridge** between Rust and Swift for seamless integration

### [Termineer](https://termineer.io/) - Autonomous AI Coding Agent
[GitHub](https://github.com/semtexzv/termineer)
Self-directed coding agent with multi-agent orchestration framework
- **Autonomous task decomposition**: Agents can break down complex tasks and execute them independently
- **Multi-agent orchestration**: Specialized agents for different domains working in coordination
- **Universal tool abstraction**: Works seamlessly across Anthropic, Google, and OpenAI models
- **Model Context Protocol (MCP)** support for extensible tool integration
- **Advanced TUI**: Real-time updates and interactive terminal interface
- **OAuth authentication** with tiered subscription model (Free/Plus/Pro)

### [Rama](https://github.com/semtexzv/rama) - LLM Implementation from Scratch (Experimental)
Experimental Rust implementation of Llama models for local inference
- **Pure Rust implementation** of Llama architecture from scratch
- **Focus on simplicity**: Minimal codebase for educational and experimental purposes
- **Research testbed** for on-device inference optimization techniques
- **Learning platform** for understanding transformer architectures

### [MML](https://github.com/semtexzv/mml) - Micro Machine Learning Library (Experimental)
Experimental ML library with autodiff and graph tensor framework for Apple Silicon
- **Automatic differentiation** engine for gradient computation
- **Computational graph** based tensor operations
- **Apple Silicon optimized**: Designed for M-series processors using both CPU and GPU
- **Clean API**: Simple interface for building and training neural networks
- **Research platform**: Testbed for ML graph optimization research
- **Implemented optimizers**: SGD with extensible optimizer framework

### [Blok3](https://blok3.io/) - Low-Latency Cryptocurrency Portfolio Provider
High-performance cryptocurrency portfolio tracking platform
- Built using self-developed Stor & Protokit libraries
- Provides extremely detailed cryptocurrency portfolio information
- **Optimized for low-latency** operation without caching
- Demonstrates practical application of custom storage and serialization libraries

### [Protokit](https://github.com/semtexzv/protokit) - High-Performance Protocol Buffers
Efficient Protocol Buffers implementation for Rust
- **Only Rust implementation** supporting full TextFormat specification
- **Competitive performance** with industry-standard `prost` library
- **Comprehensive feature set**: Binary and text format support
- Used in production for high-performance data serialization

### [Stor](https://github.com/semtexzv/stor) - Embedded Key-Value Database
High-performance, low-latency storage engine
- **Typed key-value database** for Rust projects built on RocksDB
- **Zero-copy deserialization** for optimal performance
- Served as storage engine enabling low latency for Blok3 platform
- Designed for embedded use in high-performance applications

### [LNPay](https://github.com/semtexzv/LNPay) - Lightning Network Payment Platform
Payment platform for Bitcoin Lightning Network purchases via credit cards
- **Stripe integration** for credit card processing
- **Direct Lightning Network** communication
- **On-exchange hedging** strategy to reduce transaction risk
- **Cloud-native**: Go implementation deployed on Azure Kubernetes

### [Prospector](https://github.com/semtexzv/Prospector) - Multi-Algorithm Cryptocurrency Miner
Green-field cryptocurrency mining implementation
- **Multi-algorithm support**: ~6 different mining algorithms
- **GPU acceleration**: OpenCL and CUDA implementations
- **World's best performance** on Signatum cryptocurrency
- **Extensible architecture**: Support for both CPU and GPU mining
- Written in Rust with focus on performance optimization

### [Cryptrader](https://github.com/semtexzv/cryptrader) - Distributed Algorithmic Trading System
Master's thesis project for automated cryptocurrency trading
- **Event-driven architecture** built on ZeroMQ and NATS
- **Kubernetes-native**: Designed for cloud deployment
- **Distributed system** for handling multiple exchanges and strategies
- Written in Rust for performance and reliability
- Not deployed commercially due to inherent risks in day-trading strategies

---

## Interests

Building autonomous AI systems, distributed systems architecture, machine learning infrastructure, performance optimization, and exploring the intersection of AI and software engineering.