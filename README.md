The Secure Campus Network Framework (SCNF) represents a comprehensive academic initiative I undertook to address real-world cybersecurity challenges within an educational environment. The primary objective of this project was to conceptualize and simulate the creation of a secure, scalable, and efficiently managed campus network by leveraging the latest advancements in networking and security. Rather than relying on theoretical or abstract models, I focused on implementing practical, actionable solutions that could realistically be adopted in modern academic institutions.

My design approach encompassed the entire organizational structure of a typical campus, segmenting the network into distinct departments: Administration, Faculty, Students, Library, Server Room, and Security Room. To enhance both security and network performance, I assigned each department to its own dedicated VLAN (Virtual Local Area Network). This segmentation ensures that sensitive data and resources are isolated, reducing the risk of unauthorized access and minimizing broadcast traffic, which can significantly improve the overall efficiency of the network.

Network management was further streamlined by configuring DHCP servers to automate IP address assignment, making device onboarding seamless and minimizing administrative overhead. For interdepartmental communication, I implemented inter-VLAN routing using a Router-on-a-Stick topology. This method, while straightforward, is a robust solution for enabling controlled data flow between VLANs, ensuring each department can access necessary resources without compromising security.

Security was a central concern throughout the project. To control and monitor access between different network segments, I deployed Access Control Lists (ACLs) on network devices. These ACLs are meticulously crafted to block unauthorized traffic, allowing only specific, predefined types of communication between departments. This granular level of control is essential for preventing lateral movement by potential attackers within the network.

To evaluate the effectiveness of my design and identify potential vulnerabilities, I conducted an extensive ethical hacking simulation in a controlled, virtual environment. Utilizing industry-standard tools such as Kali Linux, Metasploitable2, Nmap, Nikto, Metasploit, and Wireshark, I performed vulnerability assessments and penetration tests. This hands-on testing process allowed me to uncover realistic threat vectors that could compromise the network’s integrity. The insights gained from these simulated attacks informed a set of targeted, actionable recommendations to further strengthen the network’s security posture. These included refining ACLs, implementing stronger authentication mechanisms, regular patch management, and comprehensive user awareness training.

This project is more than a technical demonstration—it’s an interdisciplinary synthesis of skills and knowledge acquired from a diverse set of courses, including Ethical Hacking, Advanced Cyber Security (CTP), Software Project Management (SPM), and IT Acts & Cyber Laws. Integrating legal and managerial perspectives with technical expertise provided a holistic understanding of how cybersecurity frameworks must align with regulatory requirements and organizational objectives.

I managed the project lifecycle with Trello for task tracking and collaboration, and documented my process and findings using Microsoft Word and PowerPoint. I also referenced the IT Act (IndiaCode) to ensure that my proposed solutions aligned with national legal standards and compliance requirements. The entire design and testing process was conducted in a simulated environment, utilizing Cisco Packet Tracer for network modeling and security labs, ensuring no risk to real-world infrastructure.

In summary, the Secure Campus Network Framework stands as a completed academic endeavor, offering a practical blueprint for constructing resilient, secure, and manageable campus networks. This project demonstrates not only technical proficiency but also an understanding of the broader implications of cybersecurity in an academic context, preparing me for real-world challenges in the field.

Team Member

Shivam Swaraj
BCA (Cyber Security), Semester V
Apex University, Jaipur

(Individual Project)

Deployment

This project is designed and tested entirely within a virtual lab environment and has not been deployed on an actual campus network. All configurations, simulations, and security assessments were carried out using virtual tools to ensure safety and repeatability.

Technologies & Tools Used

Cisco Packet Tracer (for network design and simulation)
Kali Linux and Metasploitable2 (for ethical hacking and penetration testing)
Nmap, Nikto, Metasploit, Wireshark (for vulnerability scanning and network analysis)
Trello (for project management and workflow organization)
Microsoft Word & PowerPoint (for documentation and presentation)
IT Act Reference – IndiaCode (for legal and compliance considerations)

Project Status

The Secure Campus Network Framework project is complete, having met all academic objectives related to cybersecurity and network design. It serves as a robust demonstration of applied skills and interdisciplinary learning, with a strong focus on both security and operational efficiency.
