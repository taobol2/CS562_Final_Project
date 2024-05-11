# CS562_Final_Project Spring 2024

Taobo Liao, Taoran Li, Qiwei He

## Abstract   
 In the evolving domain of machine learning, ensuring the privacy and integrity of
 training data across multi-party computations (MPC) is paramount. Our project
 focuses on addressing the vulnerabilities of the existing MPC frameworks, particu
larly in detecting and mitigating data poisoning attacks that can compromise the
 outcomes of collaborative machine learning efforts. While platforms like Cerebro
 have advanced multi-party cryptographic collaborative learning by ensuring data
 consistency, they fall short in identifying malicious datasets introduced prior to
 computation. To counter this, we propose an enhancement of the Cerebro platform
 through several innovative methods: introducing a trusted third-party auditor with
 zero-knowledge proofs, employing anomaly detection and outlier analysis through
 normalization flows, and a novel approach of SISA (Shard, Isolated, Sliced, and
 Aggregated) training. Each strategy aims to refine the detection of poisoned data
 and to secure the model training process in MPC environments. We conduct exper
iments using datasets like MNIST to validate the efficacy of our methods against
 straightforward data perturbation attacks, providing a groundwork for further im
provements in secure, privacy-preserving machine learning protocols. Our findings
 reveal the potential of these enhancements to significantly bolster the robustness of
 MPCframeworks against sophisticated adversarial inputs.
