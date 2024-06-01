[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

## Updated on 2024.06.01
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
|**ProSecutor: Protecting Mobile AIGC Services on Two-Layer Blockchain via Reputation and Contract Theoretic Approaches**|**IEEE Transactions on Mobile Computing**| Mobile AI-Generated Content (AIGC) has achieved great attention in unleashing the power of generative AI and scaling the AIGC services. By employing numerous Mobile AIGC Service Providers (MASPs), ubiquitous and low-latency AIGC services for clients can be realized. Nonetheless, the interactions between clients and MASPs in public mobile networks, pertaining to three key mechanisms, namely MASP selection, payment scheme, and fee-ownership transfer, are unprotected. In this paper, we design the above mechanisms using a systematic approach and present the first blockchain to protect mobile AIGC, called ProSecutor. Specifically, by roll-up and layer-2 channels, ProSecutor forms a two-layer architecture, realizing tamper-proof data recording and atomic fee-ownership transfer with high resource efficiency. Then, we present the Objective-Subjective Service Assessment (OS^{2}A) framework, which effectively evaluates the AIGC services by fusing the objective service quality with the reputation-based subjective experience of the service outcome (i.e., AIGC outputs). Deploying OS^{2}A on ProSecutor, firstly, the MASP selection can be realized by sorting the reputation. Afterward, the contract theory is adopted to optimize the payment scheme and help clients avoid moral hazards in mobile networks. We implement the prototype of ProSecutor on BlockEmulator.Extensive experiments demonstrate that ProSecutor achieves 12.5x throughput and saves 67.5\% storage resources compared with BlockEmulator. Moreover, the effectiveness and efficiency of the proposed mechanisms are validated. |
|**Healthcare Applications Using Blockchain With a Cloud-Assisted Decentralized Privacy-Preserving Framework**|**IEEE Transactions on Mobile Computing**| In recent times, cloud-enabled healthcare services have gained much attention in fulfilling the analysis of privacy risks associated with effective decision management systems including trustworthiness and secure data sharing. This system has revolutionized the medical architecture to evolve unprecedented opportunities in using the technologies of next-generation networks, including services, control, and signaling, to effectively improve content delivery to individuals and organizations. However, it is a highly complex matter to distribute confidential data over a public network because data privacy and device security are at risk. As a result, a cloud-based healthcare application is introduced that integrates the computation capabilities of ubiquitous computing to provide extensive communications over dedicated Internet access in order to store health records. To manage access control mechanisms and process sensitive data without extensive computation, the existing cloud-centric systems access remote servers via dedicated networks. Based on a centralized architecture, a dedicated network uses different application domains to deliver information to the healthcare industry. Unfortunately, computation complexity greatly deteriorates the performance of peer-to-peer (P2P) communications. Thus, this paper presents a cloud-assisted decentralized privacy preserving framework (CA-DPPF) using blockchain and key agreement (KA) mechanisms to achieve secure data storage and privacy. The detailed security analysis proves that the proposed scheme fulfills the desired security properties of healthcare supply chain management (H-SCM) such as conditional traceability, data immutability, and data integrity. Overall, exploratory analysis shows that CA-DPPF guarantees better transaction efficiencies such as less latency and more throughput in order to improve the service utilization factor. |
|**An End-to-End Performance Comparison of Seven Permissioned Blockchain Systems**|**International Middleware Conference**| The emergence of numerous blockchain solutions, offering innovative approaches to optimise performance, scalability, privacy, and governance, complicates performance analysis. Reasons for the difficulty of benchmarking blockchains include, for example, the high number of system parameters to configure and the effort to deploy a blockchain network. In addition, performance data, which mostly comes from system vendors, is often opaque. We provide a reproducible evaluation of the performance of seven permissioned blockchain systems across different parameter settings. We employ an end-to-end approach, where the clients sending the transactions are fully involved in the data collection approach. Our results underscore the unique characteristics and limitations of the systems we examined. Due to the insights given, our work forms the basis for continued research to optimise the performance of blockchain systems. |
|**On State Transition Probability and Performance of Direct Acyclic Graph Based Ledgers**|**IEEE Transactions on Mobile Computing**| Direct acyclic graph (DAG) based ledgers with multi-chain structures aim to solve the technical bottlenecks associated with classical blockchain technologies in the Internet of Things (IoT). The basic working principle of DAG-based ledgers is to validate new transactions by previous transactions in order to be added to the system. During the tip selection process in the unsteady regime, the state transition probability refers to the probability of a transaction changing from the initial state to an arbitrary state. The state transition probability plays an indispensable role in the performance and security analysis of the IoT relying on DAG-based ledgers. In this paper, we derive the exact expression and an approximate expression of the state transition probability, which both are in closed form. In addition, we propose and analyze three performance metrics, i.e., the expected cumulative weight, the expected number of steps, and the confirmation failure probability, which are derived from the state transition probability and greatly enrich the performance analysis and evaluation of the IoT. Markov chain Monte Carlo (MCMC) simulations are carried out to verify the derived analytical results and provide insight into the IoT using DAG-based ledgers. |
|**Trustworthy confidential virtual machines for the masses**|**International Middleware Conference**| Confidential computing alleviates the concerns of distrustful customers by removing the cloud provider from their trusted computing base and resolves their disincentive to migrate their workloads to the cloud. This is facilitated by new hardware extensions, like AMD's SEV Secure Nested Paging (SEV-SNP), which can run a whole virtual machine with confidentiality and integrity protection against a potentially malicious hypervisor owned by an untrusted cloud provider. However, the assurance of such protection to either the service providers deploying sensitive workloads or the end-users passing sensitive data to services requires sending proof to the interested parties. Service providers can retrieve such proof by performing remote attestation while end-users have typically no means to acquire this proof or validate its correctness and therefore have to rely on the trustworthiness of the service providers. In this paper, we present Revelio, an approach that features two main contributions: i) it allows confidential virtual machine (VM)-based workloads to be designed and deployed in a way that disallows any tampering even by the service providers and ii) it empowers users to easily validate their integrity. In particular, we focus on web-facing workloads, protect them leveraging SEV-SNP, and enable end-users to remotely attest them seamlessly each time a new web session is established. To highlight the benefits of Revelio, we discuss how a standalone stateful VM that hosts an open-source collaboration office suite can be secured and present a replicated protocol proxy that enables commodity users to securely access the Internet Computer, a decentralized blockchain infrastructure. |
|**Graph Neural Network-Enhanced Reinforcement Learning for Payment Channel Rebalancing**|**IEEE Transactions on Mobile Computing**| Building on top of blockchain, payment channel networks-backed (PCNs) cryptocurrencies emerge as a promising solution for a mobile payment system with fewer intermediaries, more security, higher speed, and lower cost. A key problem for PCN is payment channel rebalancing, that is, finding a set of circular transactions that restore a PCN with skewed channel balances back into an equilibrium state. However, existing practice on payment channel rebalancing either has a hard limit on the problem size or tends to fall into local optimum. To address these challenges, we propose DRL-PCR, a Deep Reinforcement Learning-based Payment Channel Rebalancing algorithm. On one hand, DRL-PCR leverages the strong approximation ability of deep neural networks to handle large problem spaces. On the other hand, DRL-PCR decomposes the rebalancing problem into a sequence of decision-making problems and progressively builds the final solution. By aiming to find a globally optimized solution and solving the long-term optimization model of DRL, DRL-PCR is superior to greedy-based algorithms and can mitigate the risk of getting trapped in a local optimum. In particular, payment channel rebalancing typically involves dealing with graph-structured data, where the major obstacle lies in understanding the sophisticated circular dependencies between payment channels and routing paths. DRL-PCR achieves this by encoding the input data with a novel graph neural network-based model and capturing the circular dependencies through a customized message passing process. In addition, considering the distributed nature of PCN, DRL-PCR uses a leadership election protocol to elect leaders for decision-making. Evaluations on the historical data of two real-world PCNs demonstrate that DRL-PCR can restore the PCN to a more balanced state and improve the transaction throughput and success ratios by up to 2.1x and 1.6x, respectively. |
|**Attribute-Based Data Sharing Scheme Using Blockchain for 6G-Enabled VANETs**|**IEEE Transactions on Mobile Computing**| The advent of 6 G communications technology will bring about a transition from the “Internet of Everything” to the “Intelligent Connection of Everything”. 6G-enabled vehicular ad hoc networks (VANETs) will enjoy lower latency, higher speed, and greater capacity network services. Nevertheless, achieving secure data sharing will be an even tougher challenge. Given this, we propose an attribute-based data sharing scheme with blockchain for 6G-enabled VANETs. First, we propose an efficient multi-tree-based user revocation mechanism. With the Chinese remainder theorem, our mechanism supports user batch revocation and batch joining. Second, we achieve distributed data storage by utilizing the blockchain and smart contracts. To solve the problem of insufficient storage capacity on the blockchain, we adopt a combination of on-chain and off-chain storage. Third, to reduce the computation burden on users, our proposal supports online/offline encryption and verifiable outsourced decryption. Meanwhile, our mechanism supports policy hiding, data revocation, and cross-domain data sharing. The proposed scheme is proven to satisfy the indistinguishability under chosen plaintext attack (IND-CPA) in the standard model. Theoretical analysis shows that our mechanism outperforms existing schemes in functionality and security. Simulation experiments show that our proposal is efficient and suitable for 6G-enabled VANETs. |
|**DBCPA: Dual Blockchain-Assisted Conditional Privacy-Preserving Authentication Framework and Protocol for Vehicular Ad Hoc Networks**|**IEEE Transactions on Mobile Computing**| Vehicular ad hoc networks (VANETs) connect all vehicles through wireless channels. They provide extensive real-time traffic information services that improve driving safety and traffic management efficiency. However, VANETs are vulnerable to security attacks because of the open wireless nature of their communication channels. Most security mechanisms for traditional VANETs are centralized and have certain limitations in satisfying security requirements, such as anti-single-point failure, distributed security authentication of messages, and privacy preservation in VANETs. To address these issues, herein, we propose a dual blockchain-assisted conditional privacy-preserving authentication framework and protocol for VANETs. The identity authentication and privacy preservation of vehicles in VANETs can be realized without relying on a centralized trusted third party. The proposed scheme also allows for the conditional tracking of illegal vehicles. The decentralized dynamic revocation of illegal vehicles can be realized through smart contracts, rendering the scheme efficient and scalable. We implement this scheme in an Ethereum test network to demonstrate its feasibility and conduct an in-depth security analysis and comprehensive performance evaluation of the proposed scheme. The results demonstrate that the proposed scheme is an effective solution for the development of a decentralized authentication system for VANETs. |
|**Enhancing Trust and Privacy in Distributed Networks: A Comprehensive Survey on Blockchain-based Federated Learning**|**Knowledge and Information Systems**| While centralized servers pose a risk of being a single point of failure, decentralized approaches like blockchain offer a compelling solution by implementing a consensus mechanism among multiple entities. Merging distributed computing with cryptographic techniques, decentralized technologies introduce a novel computing paradigm. Blockchain ensures secure, transparent, and tamper-proof data management by validating and recording transactions via consensus across network nodes. Federated Learning (FL), as a distributed machine learning framework, enables participants to collaboratively train models while safeguarding data privacy by avoiding direct raw data exchange. Despite the growing interest in decentralized methods, their application in FL remains underexplored. This paper presents a thorough investigation into Blockchain-based FL (BCFL), spotlighting the synergy between blockchain's security features and FL's privacy-preserving model training capabilities. First, we present the taxonomy of BCFL from three aspects, including decentralized, separate networks, and reputation-based architectures. Then, we summarize the general architecture of BCFL systems, providing a comprehensive perspective on FL architectures informed by blockchain. Afterward, we analyze the application of BCFL in healthcare, IoT, and other privacy-sensitive areas. Finally, we identify future research directions of BCFL. |
|**Less payment and higher efficiency: A verifiable, fair and forward-secure range query scheme using blockchain**|**Comput. Networks**| None |
|**Improving Smart Contract Security with Contrastive Learning-based Vulnerability Detection**|**International Conference on Software Engineering**| Currently, smart contract vulnerabilities (SCVs) have emerged as a major factor threatening the transaction security of blockchain. Existing state-of-the-art methods rely on deep learning to mitigate this threat. They treat each input contract as an independent entity and feed it into a deep learning model to learn vulnerability patterns by fitting vulnerability labels. It is a pity that they disregard the correlation between contracts, failing to consider the commonalities between contracts of the same type and the differences among contracts of different types. As a result, the performance of these methods falls short of the desired level. To tackle this problem, we propose a novel Contrastive Learning Enhanced Automated Recognition Approach for Smart Contract Vulnerabilities, named Clear. In particular, Clear employs a contrastive learning (CL) model to capture the fine-grained correlation information among contracts and generates correlation labels based on the relationships between contracts to guide the training process of the CL model. Finally, it combines the correlation and the semantic information of the contract to detect SCVs. Through an empirical evaluation of a large-scale real-world dataset of over 40K smart contracts and compare 13 state-of-the-art baseline methods. We show that Clear achieves (1) optimal performance over all baseline methods; (2) 9.73%-39.99% higher F1-score than existing deep learning methods. |
|**Vehicloak: A Blockchain-Enabled Privacy-Preserving Payment Scheme for Location-Based Vehicular Services**|**IEEE Transactions on Mobile Computing**| The Internet of Vehicles (IoV) technology enables vehicles to communicate with each other, with pedestrians and with roadside infrastructures, to realize more efficient, safer and more environmentally friendly transportation. IoV also promises rich location-based services for vehicles, such as parking and toll highway. However, preserving privacy for location-based service payments emerges as a critical and challenging problem in IoV. Existing schemes rely on centralized banks for payment processing, resulting in location privacy leakage to centralized entities. In this article, we propose a decentralized privacy-preserving payment scheme named Vehicloak for IoV based on the blockchain technology. The biggest challenge is to provide location privacy for vehicles while guaranteeing correct service payments using the transparent blockchain. To tackle this challenge, we introduce a new cryptographic technique called zk-GSigproof that integrates zero-knowledge proof with group signature. Vehicloak implements this technique in a smart contract to process payment, which verifies zero-knowledge proof and group signature without leaking location information. It is not limited to IoV and can be applied in many payment scenarios. To evaluate the performance of our scheme, we implement Vehicloak on a private blockchain of 100 nodes on Aliyun, and conduct a test with up to 4,000 transactions. The experimental results prove the feasibility of Vehicloak. |
|**TBAC: A Tokoin-Based Accountable Access Control Scheme for the Internet of Things**|**IEEE Transactions on Mobile Computing**| Overprivilege Attack, a widely reported phenomenon in IoT that accesses unauthorized or excessive resources, is notoriously hard to prevent, trace and mitigate. In this paper, we propose TBAC, a Tokoin-Based Access Control model enabled by blockchain and Trusted Execution Environment (TEE) technologies, to offer fine-grained access control and strong auditability for IoT. TBAC materializes the virtual access power into a definite-amount, secure and accountable cryptographic coin, termed “tokoin” (token+coin), and manages it using atomic and accountable state-transition functions in a blockchain. A tokoin carries a fine-grained policy defined by the resource owner to specify the requirements to be satisfied before an access is granted, and the behavioral constraints that describe the correct procedure to follow during access. The strong-auditability is achieved with blockchain and a TEE-enabled trusted access control object (TACO) to ensure that all access activities are securely monitored and auditable. We prototype TBAC by implementing all its functions with well-studied cryptographic primitives over different blockchain platforms, building a TACO on top of the ARM Cortex-M33 TEE microcontroller, and constructing a user-friendly APP for regular users. A case study is finally presented to demonstrate how TBAC is employed to enable autonomous and secure in-home cargo delivery. |
|**A Decentralized Authenticated Key Agreement Scheme Based on Smart Contract for Securing Vehicular Ad-Hoc Networks**|**IEEE Transactions on Mobile Computing**| Since the communication channels in vehicular ad-hoc networks (VANETs) are wireless and open, malicious adversaries can monitor or fabricate messages transmitted across them. To secure vehicular communications, an authenticated key agreement (AKA) scheme needs to be designed for VNAETs. Traditional VANETs AKA schemes require the trusted authority (TA) to authenticate the legality of message and corresponding sender. However, the TA in these schemes is vulnerable to suffer from single-point-of-failure issues. Some blockchain-based VANETs AKA schemes have been proposed recently to address the deficiency. However, these schemes rely on the consortium or private blockchain in which TAs are still required for key generation, resulting that the practicality is limited. To solve the issue, we design a smart contract-based VANETs AKA scheme, where the AKA algorithm of our proposed scheme is implemented on smart contract deployed on a public blockchain system and the TA that is responsible for key generation will not be required. The security proof and analysis show that our proposed scheme satisfies the session-key semantic security and essential security and privacy requirements, respectively. The performance analysis demonstrates that our proposed scheme outperforms existing blockchain-based VANETs AKA schemes. |
|**Blockchain-enabled authentication framework for Maritime Transportation System empowered by 6G-IoT**|**Comput. Networks**| None |
|**LVMT: An Efficient Authenticated Storage for Blockchain**|**USENIX Symposium on Operating Systems Design and Implementation**| 
 Authenticated storage access is the performance bottleneck of a blockchain, because each access can be amplified to potentially
 O
 (log 
 n
 ) disk I/O operations in the standard Merkle Patricia Trie (MPT) storage structure. In this paper, we propose a multi-Layer Versioned Multipoint Trie (LVMT), a novel high-performance blockchain storage with significantly reduced I/O amplifications. LVMT uses the authenticated multipoint evaluation tree (AMT) vector commitment protocol to update commitment proofs in constant time. LVMT adopts a multi-layer design to support unlimited key-value pairs and stores version numbers instead of value hashes to avoid costly elliptic curve multiplication operations. In our experiment, LVMT outperforms the MPT in real Ethereum traces, delivering read and write operations six times faster. It also boosts blockchain system execution throughput by up to 2.7 times.
 |
|**Accelerating and Securing Blockchain-Enabled Distributed Machine Learning**|**IEEE Transactions on Mobile Computing**| In the Internet of Things (IoT) employing centralized machine learning, security is a major concern due to the heterogeneity of end devices. Malicious devices could launch poisoning attacks to degrade machine learning models. Distributed machine learning (DML) with blockchain provides a potential solution. Once local weights are recorded on the blockchain, model aggregation with defensive schemes can be executed on smartphones to prevent attacks. However, blockchain with the proof-of-work (PoW) consensus mechanism wastes computing resources and adds latency to DML. Computing resources can be utilized more efficiently with proof-of-useful-work (uPoW), which secures transactions by solving relevant real-world problems. We propose a novel uPoW method to minimize per-round latency of DML. The uPoW mining process schedules DML instances among multi-access edge computing (MEC) servers by solving a multi-way number partitioning problem. Moreover, poisoning attacks on heterogeneous training data pose significant challenges to blockchain-based DML. To address this problem, we propose a novel aggregation protocol, named <inline-formula><tex-math notation="LaTeX"> ${Corrected\ Krum}$ </tex-math><alternatives><mml:math><mml:mrow><mml:mi>C</mml:mi><mml:mi>o</mml:mi><mml:mi>r</mml:mi><mml:mi>r</mml:mi><mml:mi>e</mml:mi><mml:mi>c</mml:mi><mml:mi>t</mml:mi><mml:mi>e</mml:mi><mml:mi>d</mml:mi><mml:mspace width="4pt"/><mml:mi>K</mml:mi><mml:mi>r</mml:mi><mml:mi>u</mml:mi><mml:mi>m</mml:mi></mml:mrow></mml:math><inline-graphic xlink:href="leung-ieq1-3325334.gif"/></alternatives></inline-formula>, to counter such attacks and improve the convergence speed of DML. By leveraging the mean-field approximation method, training errors are corrected to reduce the negative impact of poisoning attacks. Simulation results show that our proposed blockchain approach can significantly speed up DML compared with benchmarks. |
|**BlockSense: Towards Trustworthy Mobile Crowdsensing via Proof-of-Data Blockchain**|**IEEE Transactions on Mobile Computing**| Mobile crowdsensing (MCS) can promote data acquisition and sharing among mobile devices. Traditional MCS platforms are based on a triangular structure consisting of three roles: data requester, worker (i.e., sensory data provider) and MCS platform. However, this centralized architecture suffers from poor reliability and difficulties in guaranteeing data quality and privacy, even provides unfair incentives for users. In this article, we propose a blockchain-based MCS platform, namely BlockSense, to replace the traditional triangular architecture of MCS models by a decentralized paradigm. To achieve the goal of trustworthiness of BlockSense, we present a novel consensus protocol, namely Proof-of-Data (PoD), which leverages miners to conduct useful data quality validation work instead of “useless” hash calculation. Meanwhile, in order to preserve the privacy of the sensory data, we design a homomorphic data perturbation scheme, through which miners can verify data quality without knowing the contents of the data. We have implemented a prototype of BlockSense and conducted case studies on campus, collecting over 7,000 data from workers’ mobile phones. Both simulations and real-world experiments show that BlockSense can not only improve system security, preserve data privacy and guarantee incentives fairness, but also achieve at least 5.6x faster than Ethereum smart contracts in verification efficiency. |
|**Practical Byzantine Fault Tolerance-Enhanced Blockchain-Enabled Data Sharing System: Latency and Age of Data Package Analysis**|**IEEE Transactions on Mobile Computing**| Data timeliness, privacy, and security are key enablers for data-sharing systems to support time-sensitive and mission-critical systems and applications. While blockchain-enabled data sharing frameworks can offer reliable security and privacy when properly implemented, the timeliness of data and the related latency are important issues that can limit the adoption of blockchain in large-scale mission-critical applications. This paper thus carried out a performance analysis of the blockchain-enabled data-sharing framework from latency and data age perspectives to investigate the suitability of blockchain technology in data sharing systems. To achieve this, the uniqueness of such systems such as transactions validation latency, transaction generation rate, waiting time, blockchain-appending rate, and overall communication latency were jointly studied. The communication latency was characterized following the spatiotemporal modeling approach. We further adopted the practical Byzantine fault tolerance (PBFT) consensus protocol due to its well discussed suitability in large-scale data sharing applications and captured the validation stages of such a PBFT scheme using the Erlang distribution of order <inline-formula><tex-math notation="LaTeX"> $k$ </tex-math><alternatives><mml:math><mml:mi>k</mml:mi></mml:math><inline-graphic xlink:href="cai-ieq1-3223306.gif"/></alternatives></inline-formula>. Simulations results show that various influential system parameters must be carefully considered when adopting blockchain technology in time-sensitive data sharing applications. This will guide the adoption of blockchain technology in various data sharing applications and systems. |
|**Directed dynamic attribute graph anomaly detection based on evolved graph attention for blockchain**|**Knowledge and Information Systems**| None |
|**A Blockchain-Based Distributed and Intelligent Clustering-Enabled Authentication Protocol for UAV Swarms**|**IEEE Transactions on Mobile Computing**| Unmanned aerial vehicles (UAVs) are operated remotely without the presence of a unified system of identity authentication, and wireless communications in untrusted environments can cause the loss of valuable data carried by UAVs. Traditional UAV authentication mechanisms are centralized approaches, which suffer from a single point of failure problem and may incur high complexity computations. Therefore, it is crucial to establish a distributed authentication mechanism between the ground station controller (GSC) and a UAV. Moreover, in case of UAV swarms, the high mobility of the UAVs affects the stability of UAV communications, which leads to the degradation of the UAV authentication performance. Addressing these challenges, we design a blockchain-based distributed authentication mechanism, known as SwarmAuth, for UAV swarms, where the GSC and UAVs follow a mutual authentication approach using physical unclonable functions (PUFs), and the K-means clustering-based intelligent approach is used to dynamically create location-based clusters. The blockchain helps store UAVs’ authentication information in an immutable storage and the associated smart contracts provide a convenient access control model. The security analysis of SwarmAuth is carried out through both formal and informal proofs considering general attacks. Experimental evaluation shows that SwarmAuth can assure trustworthy communications and improve the network performance. |
|**A Vehicular Trust Blockchain Framework With Scalable Byzantine Consensus**|**IEEE Transactions on Mobile Computing**| The maturing blockchain technology has gradually promoted decentralized data storage from cryptocurrencies to other applications, such as trust management, resulting in new challenges based on specific scenarios. Taking the mobile trust blockchain within a vehicular network as an example, many users require the system to process massive traffic information for accurate trust assessment, preserve data reliably, and respond quickly. While existing vehicular blockchain systems ensure immutability, transparency, and traceability, they are limited in terms of scalability, performance, and security. To address these issues, this paper proposes a novel decentralized vehicle trust management solution and a well-matched blockchain framework that provides both security and performance. The paper primarily addresses two issues: i) To provide accurate trust evaluation, the trust model adopts a decentralized and peer-review-based trust computation method secured by trusted execution environments (TEEs). ii) To ensure reliable trust management, a multi-shard blockchain framework is developed with a novel hierarchical Byzantine consensus protocol, improving efficiency and security while providing high scalability and performance. The proposed scheme combines the decentralized trust model with a multi-shard blockchain, preserving trust information through a hierarchical consensus protocol. Finally, real-world experiments are conducted by developing a testbed deployed on both local and cloud servers for performance measurements. |
|**BEET: Blockchain Enabled Energy Trading for E-Mobility Oriented Electric Vehicles**|**IEEE Transactions on Mobile Computing**| Renewable Energy Sources (RESs) are gaining considerable attention to reduce human dependence on fossil fuels and minimize harmful gases in our surroundings. Existing literature on energy trading focused on providing renewable energy to smart homes, smart buildings, and smart offices to fulfill their daily energy demands obtained from RESs. Besides, Electric Vehicles (EVs) use either power grid energy or a battery exchange mechanism to recharge their low EV batteries. The continuous use of power grids to recharge low EV batteries causes a significant load on power grids. Due to this, power grids are inadequate to fulfill the ever-increasing demands of EVs in the future. In this context, we propose a Blockchain Enabled Energy Trading (BEET) framework oriented EV charging. A system architecture of the BEET framework is presented to describe the functioning of each layer and its associated entities. We formulate an optimization problem that maximizes the revenue in the energy trading process using a knapsack optimization. Smart contracts are designed on the consortium blockchain network to sell and buy renewable energy to aggregators and from producers, respectively. Moreover, an EV charging mechanism is designed to intelligently allocate renewable energy to consumers at a low price. A comparative analysis is performed with state-of-the-art works in terms of charging price, revenue, throughput, and latency. The results indicate that the BEET framework outperforms compared to state-of-the-art works to address the renewable energy demand problem to realize E-mobility. It is clarified that the data considered in the experimental analysis were obtained from statistical simulations in realistic E-Mobility environment settings. |

<p align=right>(<a href=#Updated-on-20240601>back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[contributors-url]: https://github.com/Vincentqyw/cv-arxiv-daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[forks-url]: https://github.com/Vincentqyw/cv-arxiv-daily/network/members
[stars-shield]: https://img.shields.io/github/stars/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[stars-url]: https://github.com/Vincentqyw/cv-arxiv-daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/Vincentqyw/cv-arxiv-daily.svg?style=for-the-badge
[issues-url]: https://github.com/Vincentqyw/cv-arxiv-daily/issues

