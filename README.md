[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## Updated on 2024.03.04
> Usage instructions: [here](./docs/README.md#usage)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href=#blockchain>blockchain</a></li>
  </ol>
</details>

## blockchain

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**An End-to-End Performance Comparison of Seven Permissioned Blockchain Systems**|**International Middleware Conference**| The emergence of numerous blockchain solutions, offering innovative approaches to optimise performance, scalability, privacy, and governance, complicates performance analysis. Reasons for the difficulty of benchmarking blockchains include, for example, the high number of system parameters to configure and the effort to deploy a blockchain network. In addition, performance data, which mostly comes from system vendors, is often opaque. We provide a reproducible evaluation of the performance of seven permissioned blockchain systems across different parameter settings. We employ an end-to-end approach, where the clients sending the transactions are fully involved in the data collection approach. Our results underscore the unique characteristics and limitations of the systems we examined. Due to the insights given, our work forms the basis for continued research to optimise the performance of blockchain systems. |
|**Trustworthy confidential virtual machines for the masses**|**International Middleware Conference**| Confidential computing alleviates the concerns of distrustful customers by removing the cloud provider from their trusted computing base and resolves their disincentive to migrate their workloads to the cloud. This is facilitated by new hardware extensions, like AMD's SEV Secure Nested Paging (SEV-SNP), which can run a whole virtual machine with confidentiality and integrity protection against a potentially malicious hypervisor owned by an untrusted cloud provider. However, the assurance of such protection to either the service providers deploying sensitive workloads or the end-users passing sensitive data to services requires sending proof to the interested parties. Service providers can retrieve such proof by performing remote attestation while end-users have typically no means to acquire this proof or validate its correctness and therefore have to rely on the trustworthiness of the service providers. In this paper, we present Revelio, an approach that features two main contributions: i) it allows confidential virtual machine (VM)-based workloads to be designed and deployed in a way that disallows any tampering even by the service providers and ii) it empowers users to easily validate their integrity. In particular, we focus on web-facing workloads, protect them leveraging SEV-SNP, and enable end-users to remotely attest them seamlessly each time a new web session is established. To highlight the benefits of Revelio, we discuss how a standalone stateful VM that hosts an open-source collaboration office suite can be secured and present a replicated protocol proxy that enables commodity users to securely access the Internet Computer, a decentralized blockchain infrastructure. |
|**DBCPA: Dual Blockchain-Assisted Conditional Privacy-Preserving Authentication Framework and Protocol for Vehicular Ad Hoc Networks**|**IEEE Transactions on Mobile Computing**| Vehicular ad hoc networks (VANETs) connect all vehicles through wireless channels. They provide extensive real-time traffic information services that improve driving safety and traffic management efficiency. However, VANETs are vulnerable to security attacks because of the open wireless nature of their communication channels. Most security mechanisms for traditional VANETs are centralized and have certain limitations in satisfying security requirements, such as anti-single-point failure, distributed security authentication of messages, and privacy preservation in VANETs. To address these issues, herein, we propose a dual blockchain-assisted conditional privacy-preserving authentication framework and protocol for VANETs. The identity authentication and privacy preservation of vehicles in VANETs can be realized without relying on a centralized trusted third party. The proposed scheme also allows for the conditional tracking of illegal vehicles. The decentralized dynamic revocation of illegal vehicles can be realized through smart contracts, rendering the scheme efficient and scalable. We implement this scheme in an Ethereum test network to demonstrate its feasibility and conduct an in-depth security analysis and comprehensive performance evaluation of the proposed scheme. The results demonstrate that the proposed scheme is an effective solution for the development of a decentralized authentication system for VANETs. |
|**Less payment and higher efficiency: A verifiable, fair and forward-secure range query scheme using blockchain**|**Comput. Networks**| None |
|**Vehicloak: A Blockchain-Enabled Privacy-Preserving Payment Scheme for Location-Based Vehicular Services**|**IEEE Transactions on Mobile Computing**| The Internet of Vehicles (IoV) technology enables vehicles to communicate with each other, with pedestrians and with roadside infrastructures, to realize more efficient, safer and more environmentally friendly transportation. IoV also promises rich location-based services for vehicles, such as parking and toll highway. However, preserving privacy for location-based service payments emerges as a critical and challenging problem in IoV. Existing schemes rely on centralized banks for payment processing, resulting in location privacy leakage to centralized entities. In this article, we propose a decentralized privacy-preserving payment scheme named Vehicloak for IoV based on the blockchain technology. The biggest challenge is to provide location privacy for vehicles while guaranteeing correct service payments using the transparent blockchain. To tackle this challenge, we introduce a new cryptographic technique called zk-GSigproof that integrates zero-knowledge proof with group signature. Vehicloak implements this technique in a smart contract to process payment, which verifies zero-knowledge proof and group signature without leaking location information. It is not limited to IoV and can be applied in many payment scenarios. To evaluate the performance of our scheme, we implement Vehicloak on a private blockchain of 100 nodes on Aliyun, and conduct a test with up to 4,000 transactions. The experimental results prove the feasibility of Vehicloak. |
|**BlockSense: Towards Trustworthy Mobile Crowdsensing via Proof-of-Data Blockchain**|**IEEE Transactions on Mobile Computing**| Mobile crowdsensing (MCS) can promote data acquisition and sharing among mobile devices. Traditional MCS platforms are based on a triangular structure consisting of three roles: data requester, worker (i.e., sensory data provider) and MCS platform. However, this centralized architecture suffers from poor reliability and difficulties in guaranteeing data quality and privacy, even provides unfair incentives for users. In this article, we propose a blockchain-based MCS platform, namely BlockSense, to replace the traditional triangular architecture of MCS models by a decentralized paradigm. To achieve the goal of trustworthiness of BlockSense, we present a novel consensus protocol, namely Proof-of-Data (PoD), which leverages miners to conduct useful data quality validation work instead of “useless” hash calculation. Meanwhile, in order to preserve the privacy of the sensory data, we design a homomorphic data perturbation scheme, through which miners can verify data quality without knowing the contents of the data. We have implemented a prototype of BlockSense and conducted case studies on campus, collecting over 7,000 data from workers’ mobile phones. Both simulations and real-world experiments show that BlockSense can not only improve system security, preserve data privacy and guarantee incentives fairness, but also achieve at least 5.6x faster than Ethereum smart contracts in verification efficiency. |
|**Practical Byzantine Fault Tolerance-Enhanced Blockchain-Enabled Data Sharing System: Latency and Age of Data Package Analysis**|**IEEE Transactions on Mobile Computing**| Data timeliness, privacy, and security are key enablers for data-sharing systems to support time-sensitive and mission-critical systems and applications. While blockchain-enabled data sharing frameworks can offer reliable security and privacy when properly implemented, the timeliness of data and the related latency are important issues that can limit the adoption of blockchain in large-scale mission-critical applications. This paper thus carried out a performance analysis of the blockchain-enabled data-sharing framework from latency and data age perspectives to investigate the suitability of blockchain technology in data sharing systems. To achieve this, the uniqueness of such systems such as transactions validation latency, transaction generation rate, waiting time, blockchain-appending rate, and overall communication latency were jointly studied. The communication latency was characterized following the spatiotemporal modeling approach. We further adopted the practical Byzantine fault tolerance (PBFT) consensus protocol due to its well discussed suitability in large-scale data sharing applications and captured the validation stages of such a PBFT scheme using the Erlang distribution of order <inline-formula><tex-math notation="LaTeX"> $k$ </tex-math><alternatives><mml:math><mml:mi>k</mml:mi></mml:math><inline-graphic xlink:href="cai-ieq1-3223306.gif"/></alternatives></inline-formula>. Simulations results show that various influential system parameters must be carefully considered when adopting blockchain technology in time-sensitive data sharing applications. This will guide the adoption of blockchain technology in various data sharing applications and systems. |
|**Directed dynamic attribute graph anomaly detection based on evolved graph attention for blockchain**|**Knowledge and Information Systems**| None |

<p align=right>(<a href=#Updated-on-20240304>back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[contributors-url]: https://github.com/Vincentqyw/cv-arxiv-daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[forks-url]: https://github.com/Vincentqyw/cv-arxiv-daily/network/members
[stars-shield]: https://img.shields.io/github/stars/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[stars-url]: https://github.com/Vincentqyw/cv-arxiv-daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[issues-url]: https://github.com/Vincentqyw/cv-arxiv-daily/issues

