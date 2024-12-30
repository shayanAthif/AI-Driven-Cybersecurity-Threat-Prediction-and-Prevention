# DDoS Attack Detection using Neural Networks

## Project Overview
This project compares the effectiveness of Deep Neural Networks (DNN) and Graph Neural Networks (GNN) for detecting Distributed Denial of Service (DDoS) attacks. The models leverage their unique strengths, with DNNs excelling in high-volume attack detection and GNNs showcasing superior performance in identifying subtle, distributed attack patterns that traditional DNNs might miss.

## Key Findings

### DNN Strengths:
- **High Accuracy for High-Volume Attacks**: Achieved 99.34% accuracy for detecting TCP flood attacks.
- **Fast Processing**: Efficient at handling straightforward attack patterns.
- **Real-Time Detection**: Ideal for detecting obvious threats in real-time.

### GNN Advantages:
- **Effective for Stealth Attacks**: Superior at detecting low-volume, subtle attack patterns (97.56% accuracy compared to DNN's 91.23%).
- **Distributed Attack Detection**: Better at capturing relationships between network flows, enabling detection of complex, evolving threats.
- **Enhanced Understanding of Network Topology**: Captures and utilizes relationships in data to detect attack signatures more effectively.

### Performance Comparison:
| **Attack Type**       | **DNN Accuracy** | **GNN Accuracy** |
|------------------------|------------------|------------------|
| TCP Floods            | 99.34%          | 98.76%          |
| UDP Floods            | 98.87%          | 98.45%          |
| HTTP Floods           | 98.56%          | 97.89%          |
| Low-Volume Attacks    | 91.23%          | 97.56%          |

## Technology Stack
- **Programming Language**: Python 3.8+
- **Frameworks**: PyTorch, PyTorch Geometric
- **Libraries**: NumPy, Pandas, Scikit-learn

## Key Features
- **Real-Time Detection**: Capable of detecting DDoS attacks as they occur.
- **Multi-Attack Pattern Support**: Handles diverse attack types, including high-volume and stealth attacks.
- **Performance Metrics Tracking**: Includes detailed accuracy and performance comparisons.
- **Model Comparison**: Highlights the complementary strengths of DNN and GNN models.

---

This project demonstrates how neural networks can complement each other to provide robust and adaptive defenses against evolving cyber threats. For more information, feel free to explore the codebase and supporting documentation.
