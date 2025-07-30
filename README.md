---

### 📂 ArchEval Benchmark Dataset - README

---

#### 🏆 Dataset Overview  
**ArchEval Benchmark** is an open-source dataset for evaluating software architecture capabilities. It features 8 curated open-source repositories spanning microservices, middleware, and AI frameworks. Each project includes three core components:  
- **GitHub Repository Name** (URL)  
- **Architecture Diagram** (Image Format)
- **Architecture Documentation** (PDF format)  

---

#### 📊 Repository Metadata

|  | Repository Name                                                 | Architecture Diagram | #Files | Top 3 Tech Stacks                          |
|---|-----------------------------------------------------------------------------------|----------------------|-------|--------------------------------------------|
| 1 | [hashicorp/consul](https://github.com/hashicorp/consul)                           | ![arch diagram](./repos%20with%20arch_doc/1_hashicorp:consul.png) | 3,684 | Go(2361), JS/TS(1164), YAML(78)            |
| 2 | [spring-framework](https://github.com/spring-projects/spring-framework)           | ![arch diagram](./repos%20with%20arch_doc/2_spring-projects:spring-framework.png) | 9,370 | Java(8986), Kotlin(328), YAML(25)          |
| 3 | [apache/zookeeper](https://github.com/apache/zookeeper)                           | ![arch diagram](./repos%20with%20arch_doc/3_apache:zookeeper.png) | 1,115 | Java(950), C/C++(59), Python(36)           |
| 4 | [mindspore-ai/mindspore](https://github.com/mindspore-ai/mindspore)               | ![arch diagram](./repos%20with%20arch_doc/4_mindspore-ai:mindspore.jpeg) | 16,525| C/C++(9459), Python(6225), YAML(753)        |
| 5 | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes)                            | ![arch diagram](./repos%20with%20arch_doc/5_kubernetes:kubernetes.svg) | 21,743| Go(15941), YAML(5225), Markdown(562)       |
| 6 | [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow)                            | ![arch diagram](./repos%20with%20arch_doc/6_tensorflow:tensorflow.png) | 10,846| C/C++(5973), Python(3133), Markdown(1187)  |
| 7 | [apache/kafka](https://github.com/apache/kafka)                                   | ![arch diagram](./repos%20with%20arch_doc/7_apache:kafka.png) | 5,876 | Java(5549), Python(178), YAML(65)          |
| 8 | [istio/istio](https://github.com/istio/istio)                                     | ![arch diagram](./repos%20with%20arch_doc/8_istio:istio.svg) | 4,611 | YAML(2595), Go(1886), Markdown(87)         |

> 💡 **Tech Stack Note**: Includes core languages and configuration files (YAML/HTML/MD)

---

#### 🛠️ Use Cases  
- Architecture reverse engineering  
- Code-documentation consistency validation  
- Cross-project architectural pattern analysis  
- AI-based architecture generation  

---

#### 🔗 Data Access  
```bash
git clone https://github.com/panrusheng/arch-eval-benchmark
```

---

#### 🤝 Contribution Guidelines  
1. Follow directory structure: `{number}_{org}/project.{pdf|png|jpg|svg}`  
   (Example: `9_neworg/project.pdf`)  
2. Diagrams should match PDF filenames  
3. New repositories should exceed 1,000 files  