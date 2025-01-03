# Section 1: Digital Transformation with Google Cloud (~17% of the exam)

## 1.1 - Why Cloud Technology is Transforming Business

Explain why and how the cloud is revolutionizing businesses.

- Define the terms: cloud, cloud technology, data, digital transformation, cloud-native, open source, open standard.
  - Cloud: A cloud refers to a model of computing that delivers on-demand access to a shared pool of configurable computing resources such as compute, storage, and networking. It provides flexibility, scalability, and cost efficiency, catering to diverse organizational needs and business goals.
    - Source: ChatGPT summary of ["Types of Cloud Computing Deployment Models"](https://cloud.google.com/learn/what-is-cloud-computing).
  - Cloud Technology: the on-demand availability of computing resources (such as storage and infrastructure), as services over the internet. It eliminates the need for individuals and businesses to self-manage physical resources themselves, and only pay for what they use.
    - Source: https://cloud.google.com/learn/what-is-cloud-computing
  - Data: data is a collection of facts, information, and statistics and this can be in various forms such as numbers, text, sound, images, or any other format.
    - Source: https://www.geeksforgeeks.org/what-is-data/
  - Digital Transformation: when an organization takes advantage of new technologies to redesign and redefine relationships with their customers, employees, and partners.
    - Source: https://cloud.google.com/learn/what-is-digital-transformation
  - Cloud-Native: an approach to building and running scalable applications to take full advantage of cloud-based services and delivery models.
    - Source: https://cloud.google.com/learn/what-is-cloud-native
  - Open Source: a decentralized production model that allows anyone to modify and share technology because its design is publicly accessible.
    - Source: https://aws.amazon.com/what-is/open-source/
  - Open Standard: a standard that is freely available for adoption, implementation and updates.
    - Source: https://www.ibm.com/think/topics/open-standards-vs-open-source-explanation
- Describe the differences between cloud technology and traditional or on-premises technology.
  - Cloud computing differs from traditional on-premises IT primarily in flexibility, cost, and management. On-premises requires significant upfront investment in hardware and software, with in-house teams handling maintenance, security, and scaling. In contrast, cloud computing operates on a pay-as-you-go model, offering scalable, internet-based services managed by third-party providers, which reduce maintenance burdens and enhance accessibility. While on-premises offers more control and can be better for strict compliance needs, cloud solutions excel in adaptability and cost efficiency.
    - Source: https://cloud.google.com/learn/what-is-cloud-computing
- Explain the benefits of cloud technology to a business’ digital transformation.
  - this technology is scalable, exible, agile, secure, cost-effective and offers strategic value.
    - Source: https://cloud.google.com/learn/advantages-of-cloud-computing & https://cloud.google.com/learn/what-is-digital-transformation
- Describe the primary benefits of on-premises infrastructure, public cloud, private cloud, hybrid cloud, and multicloud and differentiate between them.

| **Factor**              | **On-Premises**        | **Public Cloud**        | **Private Cloud**        | **Hybrid Cloud**         | **Multicloud**          |
|--------------------------|------------------------|--------------------------|---------------------------|---------------------------|--------------------------|
| **Ownership**            | Organization           | Cloud Provider           | Organization/Provider     | Mixed                    | Mixed                   |
| **Control**              | Full                  | Limited                  | High                     | Moderate                 | Moderate                |
| **Cost Structure**       | Capital Expense (CapEx)| Operational Expense (OpEx)| CapEx/OpEx               | Mixed                    | OpEx                    |
| **Scalability**          | Limited               | High                     | Limited                  | Moderate                 | High                    |
| **Use Case**             | Compliance-heavy workloads | Dynamic, unpredictable workloads | Secure, sensitive workloads | Mixed workloads | Multi-provider resilience |

- Comparison Table:
  - Various Categories:
    - Source: ChatGPT summary table from direct text copy+paste prompt.
- Describe the main business transformation benefits of Google Cloud: intelligence, freedom, collaboration, trust, and sustainability.
  - Modernize infrastructure, manage data, gain insight, breka down team silos, solve business problems, and realize cost savings.
    - Source: https://cloud.google.com/learn/what-is-digital-transformation
- Describe the implications and risks for organizations that do not adopt new technology.
  - You run the risk of sacrificing fleixbility, the ability to experience with new ideas, measurement and data analysis, cross-team collaboration, delivering more value to customers, and a lack of agility.
    - Source: https://cloud.google.com/learn/what-is-digital-transformation
- Describe the drivers and challenges that lead organizations to undergo a digital transformation.
  - The primary drivers are closely aligned with the benefits already described above. The challenges come in the way of cultural resistance, skill gaps, legacy systems, budget constraints, data privacy and security, undefined goals, rapid technology change, and interoperability issues.
    - Source: ChatGPT outline of challenges mixed with benefits described in https://cloud.google.com/learn/what-is-digital-transformation
- Describe the transformation cloud and how it accelerates an organization’s digital transformation through app and infrastructure modernization, data democratization, people connections, and trusted transactions.
  - This powerful technology platform is designed to accelerate digital transformation for any organization by bringing five business-critical capabilities to our shared customers:
    - The ability to build open data clouds to derive insights and intelligence from data.
    - Open infrastructure that enables customers to run applications and store data where it makes the most sense.
    - A culture of collaboration built on Google Workspace that brings people together to connect and create from anywhere, enabling teams to achieve more.
    - The same trusted environment that Google uses to secure systems, data, apps, and customers from fraudulent activity, spam, and abuse.
    - And a foundational platform that uses efficient technology and innovation to drive cost savings and create a more sustainable future for everyone.
    - Source: https://cloud.google.com/blog/topics/partners/maximize-our-shared-journey-with-the-transformation-cloud

## 1.2 - Fundamental Cloud Concepts

Explain general cloud concepts.

- Describe how transitioning to a cloud infrastructure affects flexibility, scalability, reliability, elasticity, agility, and total cost of ownership (TCO). Apply these concepts to various business use cases.
  - Cloud computing gives your business more flexibility. You can quickly scale resources and storage up to meet business demands without having to invest in physical infrastructure. Companies don’t need to pay for or build the infrastructure needed to support their highest load levels. Likewise, they can quickly scale down if resources aren’t being used.  The cloud delivers more flexibility and reliability, increased performance and efficiency, and helps to lower IT costs. It also improves innovation, allowing organizations to achieve faster time to market and incorporate AI and machine learning use cases into their strategies.
    - Source: https://cloud.google.com/learn/advantages-of-cloud-computing
    - Source: ChatGPT provided use cases and TCO information
- Explain how an organization’s transition from an on-premises environment to the cloud shifts their capital expenditures (CapEx) to operational expenditures (OpEx), and how that affects their total cost of ownership (TCO).
  - Cloud infrastructure allows businesses to experiment with new tools, deploy services globally, and support remote workforces without upfront hardware investment. A startup can deploy applications and test them on GCP without heavy initial investments. It's also expensive to build and maintain infrastructure hosted in a data center. Hostings costs for hardware, replacements/upgrades, security, power, etc. are expensive and require upfront capital in addition to regular operational overhead costs.
    - Source: My brain and ChatGPT. If it makes you feel any better I have an MBA so I feel qualified to answer this question as there was no TCO documentation provided by google.
- Identify when private, hybrid, or multicloud infrastructures best apply to different business use cases.
  - Public clouds are run by third-party cloud service providers. They offer compute, storage, and network resources over the internet, enabling companies to access shared on-demand resources based on their unique requirements and business goals. Private clouds are built, managed, and owned by a single organization and privately hosted in their own data centers, commonly known as “on-premises” or “on-prem.” They provide greater control, security, and management of data while still enabling internal users to benefit from a shared pool of compute, storage, and network resources. Hybrid clouds combine public and private cloud models, allowing companies to leverage public cloud services and maintain the security and compliance capabilities commonly found in private cloud architectures.
  - Source: https://cloud.google.com/learn/what-is-cloud-computing
- Define basic network infrastructure terminology, including: IP address; internet service provider (ISP); domain name server (DNS), regions, and zones; fiber optics; subsea cables; network edge data centers, latency; and bandwidth.
  - IP Address: the unique identifying number assigned to every device connected to the internet.
    - Source: https://www.fortinet.com/resources/cyberglossary/what-is-ip-address
  - ISP: a company that provides individuals and organizations access to the internet and other related services. 
    - Source: https://www.techtarget.com/whatis/definition/ISP-Internet-service-provider
  - DNS: It is essentially the “phone book” of the internet, translating user-friendly domain names (like www.example.com) into numerical IP addresses (such as 192.0.1) that computers and network devices use to locate one another on the internet.
    - Source: https://www.geeksforgeeks.org/whats-is-domain-name-systemdns/
  - Regions: Regions are collections of zones. Zones have high-bandwidth, low-latency network connections to other zones in the same region. 
    - Source: https://cloud.google.com/compute/docs/regions-zones
  - Zones: A zone is a deployment area within a region.
    - Source: https://cloud.google.com/compute/docs/regions-zones
  - Fiber Optics: Fiber optics refers to the technology and method of transmitting data as light pulses along a glass or plastic strand or fiber.
    - Source: https://www.geeksforgeeks.org/fiber-optics-and-types/
  - Subsea Cables: Subsea cables are a crucial component of the modern global telecommunications network, enabling the transmission of data and communication between continents and countries. These cables are laid on the seabed and connect various land-based communication networks, allowing for the seamless exchange of information across vast distances.
    - Sorce: https://umatechnology.org/what-are-subsea-cables-and-why-are-they-important/
  - Network Edge Data Centers: These sites are sometimes referred to as points of presence or PoPs. Google Cloud offers connections to Google Cloud services from over 100 locations across many metropolitan areas.
    - Source: https://cloud.google.com/vpc/docs/edge-locations
  - Bandwidth: Network bandwidth is the maximum capacity of a wired or wireless communications link to deliver data via a network connection in a given amount of time.
    - Source: https://www.geeksforgeeks.org/what-is-bandwidth-definition-working-importance-uses/
- Discuss how Google Cloud supports digital transformation with global infrastructure and data centers connected by a fast, reliable network.
  - 100s of 1000s of miles of fiber optic cable including more than a dozen subsea cables are laid out between the data center and internet facing WANs. A machine gets connected from the internet via the public WAN and gets connected to other machines on the network via the private WAN. For example, when you send a packet from your virtual machine running in the cloud in one region to a GCS bucket in another, the packet does not leave the Google network backbone. In addition, network load balancers and layer 7 reverse proxies are deployed at the network edge, which terminates the TCP/SSL connection at a location closest to the user — eliminating the two network round trips needed to establish an HTTPS connection.
    - Source: https://cloud.google.com/blog/topics/developers-practitioners/google-cloud-networking-overview

## 1.3 - Cloud Computing Models and Shared Responsibility

