# Definitions in the data extraction and classification 

## Class definitions

### Research Type
- Evaluation Research (ER): It is the investigation of a problem or an implementation of a technique in practice \cite{wieringa2006requirements}. We regarded surveys and reviews as this type.
- Proposal of Solution (PS): It proposes a solution technique and argues for its relevance, without a full-blown validation, which must be novel, or at least a significant improvement of an existing technique \cite{wieringa2006requirements}. It should mainly focus on the solution itself.
- Validation Research (VR): It investigates the properties of a solution proposal that has not yet been implemented in practice. The solution may have been proposed somewhere else \cite{wieringa2006requirements}. 
- Philosophical Paper (PP): It sketches a new way of looking at things, a new conceptual framework, etc. \cite{wieringa2006requirements}. 
- Opinion Paper (OP): It contains the author's opinion about what is wrong or good about something, how we should do something, etc. \cite{wieringa2006requirements}. 
- Personal Experience Paper (PEP): It describes the personal experience and emphasize what and not why \cite{wieringa2006requirements}. 

### Security countermeasures
- Anomaly detection: Anomaly or intrusion detection methods of a system, e.g. a specification-based or machine-learning-based algorithm to detect the anomaly.
- Anomaly reaction: Strategies or methods of system reaction when anomaly or intrusion has been detected, e.g. a method to disable the attacker when being detected.
- Hardware support for security: Research on hardware to support better security countermeasures, e.g. a hardware accelerator for cryptographic calculation, realize a secure protocol in hardware.
- Key management: Approach for key management in security mechanisms, e.g. key exchange protocols, methods of generating and storing keys, etc.
- Secure communication scheme: Protocols or mechanisms to ensure the security of the data transmission in various networks, e.g. secure communication protocol, ID shuffling mechanisms, etc.
- Secure component design: Security design methods for a single component in a system, e.g. a secure gateway, secure ECU design, etc.
- Security mechanism at application layers: Mechanisms that are specific for a type of applications, e.g. a secure protocol for Unified Diagnostic Service in vehicles, a secure strategy for braking dynamics of cooperative driving, etc.
- System security design: System-level design approaches like overall design architecture, framework, etc., e.g. distributed firewall deployment, a comprehensive framework including a set of countermeasures to protect the system.
- Others: Other topics that are relevant but cannot be classified into the rest classes, e.g. a study of bit level permutation which is used in the cryptographic environment.

### Properties concerned
- Effectiveness: Whether the solution is effective to solve the problem. Concrete metrics in this class include detection accuracy metrics (e.g. precision, recall, true positive, true negative, false positive, false negative, f-score), output randomness, etc.
- Efficiency: Whether the solution is efficient. Typical metrics in this class are latency, detection speed, round trip time, standby time, process throughput, etc.
- Performance: The performance metrics of the system include network throughput, busload, bandwidth, and metrics related to the system quality (e.g. QoS, robustness, reliability, etc.). This class investigates the impacts of the countermeasures on the original system.
- Resource: This class represents the resource required by the proposed solution, like financial or computational cost, memory consumption, etc.
- Compatibility: Whether the solution is compatible with other contexts, e.g. be applicable for other media types, be compatible for other protocols.

### Map of Security Goals and Related Attacks or Mechanisms

\textbf{Security Goal} & \textbf{Relevant attack or mechanism} \\
\hline
(Data Origin) Authenticity & Forging or replacing frames, spoofing, fuzzing attack, masquerading frames, message injection, cloaking attack, fabrication, man-in-the-middle attack \\
\hline
Integrity & Manipulation, tampering, modifying data fields \\
\hline
Authorization & Access control, unauthorized access and usage \\
\hline
Freshness & Replay attack \\
\hline
Non-repudiation & N/A. No study in this class was found. \\
\hline
Privacy & N/A. Studies explicitly mentioned privacy were classified in this class. \\
\hline
Anonymity & N/A. No study in this class was found. \\
\hline
Confidentiality & Sniffing, reverse engineering, inspectation, message encryption, eavesdropping \\
\hline
Availability & Denial-of-Service (Dos) attack, interruption, suspension attack, message dropping \\
\hline

### Further work
- Improving performance: To improve the performance of the proposed solutions, including improving the practicability or effectiveness, implementing HW modules, overcoming current limitations, reducing cost, etc.
- Extending application scope: To extend application scope for more scenarios, including fighting against or detecting more attacks, integrating the proposed solution with other protocols, supporting in other contexts, trying other HWs, etc.
- Further evaluation: To evaluate the proposed solution under other conditions, including with a more extensive set of attacks, with other parameters, with real-world data and scenarios, with large scale, etc., or to investigate and compare the solution with other relevant ones.
- Adding features: To add new functional features to the proposed solution or to integrate the proposed solution with other methods, like adding a reaction process after the anomaly detection, etc.
- Exploiting other methods: To find other possible solutions for the mentioned issues or other problems, which is completely different from the proposed solution.
- None: No concrete future work is mentioned in the paper.


