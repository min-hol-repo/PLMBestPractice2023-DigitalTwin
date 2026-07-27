# Microsoft x NVIDIA – Cloud-Based Digital Twin Strategy

> 🇰🇷 [한국어로 읽기](README_KR.md)

---

| | |
|:---|:---|
| **Author** | KyoungMin Kang |
| **GitHub** | [github.com/min-hol-repo](https://github.com/min-hol-repo) |
| **Role** | Sr. Cloud Solution Architect at Microsoft |
| **Specialization** | HPC for cloud-based data analysis and technical support for smart factories |
| **Description** | A practical guide to implementing cloud-based Digital Twins in manufacturing using Microsoft Azure and NVIDIA Omniverse. |
| **Published** | July 12, 2023 |

---

## Table of Contents

- [The Evolution of Cloud-Based Digital Twins](#the-evolution-of-cloud-based-digital-twins)
- [Ontology-Centric Digital Feedback Loops](#ontology-centric-digital-feedback-loops)
- [Azure Digital Twins and NVIDIA Omniverse](#azure-digital-twins-and-nvidia-omniverse)
- [Step-by-Step Implementation of Cloud-Based Digital Twins](#step-by-step-implementation-of-cloud-based-digital-twins)
- [HPC for Digital Twin Analysis and Simulation](#hpc-for-digital-twin-analysis-and-simulation)
- [Conclusion](#conclusion)

---

## The Evolution of Cloud-Based Digital Twins

Digital Twins, a major focus for modern enterprises, originated in the early 2000s within R&D and product-centric engineering. Introduced as the "Mirrored Spaces Model" in a 2002 PLM course at the University of Michigan, the concept referred to a virtual system containing all information about a physical counterpart.

As 3D CAD adoption accelerated in the mid-2000s, 3D-centric engineering and manufacturing digital twins became prevalent. Companies developed "Digital Mockups" prior to mass production, utilizing 1:1 scale virtual assemblies for simulation and model-based analysis. This 3D-driven approach expanded into digital process design and additive manufacturing (3D printing).

Since the mid-2010s, the integration of IoT (Internet of Things) and CPS (Cyber-Physical Systems) has enabled the seamless, data-driven unification of physical and virtual worlds. The term CPS has since evolved into the broader "Digital Twin" concept, while manufacturing IoT has advanced into IIoT (Industrial IoT). During this period, research flourished on real-time monitoring via IoT and predictive maintenance through machine learning. However, traditional SCADA systems faced limitations in integrating data across globally dispersed factory lines. This naturally led to the rise of Cloud-based IIoT, with cloud providers like Microsoft entering the sector to supply scalable IoT, Big Data, and AI platforms.

Today, the advancement of VR (Virtual Reality) and MR (Mixed Reality) is fueling the growth of industrial Metaverses. Companies like NVIDIA provide cloud-based platforms powered by GPUs to design, develop, and manage these industrial metaverse applications.

![Figure 1 - The Evolution of Digital Twins](media/image4.png)

> *Figure 1 – The Evolution of Digital Twins*

---

## Ontology-Centric Digital Feedback Loops

To effectively implement diverse objects in manufacturing, ontology-based digital twin models are spreading through open communities. An ontology defines the properties and relationships of objects as data-driven entities in a graph format.

![Figure 2 - Ontology-Centric Digital Feedback Loops](media/image6.png)

> *Figure 2 – Ontology-Centric Digital Feedback Loops*

Through the **Digital Twins Consortium**, many companies are co-developing ontology specifications and industry-specific templates. Notably, **DTDL (Digital Twins Definition Language)**—an open-source language for describing digital twin models—is gaining traction across industries due to its solution-agnostic nature. By leveraging DTDL-based standard templates for smart buildings, cities, energy, and manufacturing (available via GitHub), organizations can rapidly build structured digital twins without defining every relationship from scratch.

![Figure 3 - Industry-Standard Shared Ontology Templates](media/image3.png)

> *Figure 3 – Industry-Standard Shared Ontology Templates*

---

## Azure Digital Twins and NVIDIA Omniverse

Microsoft's **Azure Digital Twins** is a data-driven platform that supports the creation of digital twins using real-time data from Edge and IoT devices.

**NVIDIA Omniverse Cloud**, hosted on Microsoft Azure, supports the entire manufacturing lifecycle from planning to execution. Leveraging NVIDIA's GPU expertise, it provides photorealistic digital twin environments and robust simulation capabilities. Results from external simulation tools can be deployed via NVIDIA Omniverse's "Nucleus." (NVIDIA Omniverse on Azure was slated for release in late 2023).

![Figure 4 - NVIDIA Omniverse on Azure](media/image2.png)

> *Figure 4 – NVIDIA Omniverse on Azure · [nvidia.com/en-us/omniverse](https://www.nvidia.com/en-us/omniverse/)*

---

## Step-by-Step Implementation of Cloud-Based Digital Twins

Manufacturing data is categorized into static and dynamic types.

| Type | Description |
|:---|:---|
| **Static Data** | Production planning data generated prior to mass production |
| **Dynamic Data** | Real-time data generated during production, focused on measurement |

Quantitative measurement of KPIs is achieved by aggregating data collected via Edge Computing and IoT. This data is then used to train AI models or run simulations for predictive services, which are delivered to users through dashboards or NVIDIA's 3D environments.

![Figure 5 - Cloud-Based Step-by-Step Digital Twin Implementation](media/image5.png)

> *Figure 5 – Cloud-Based Step-by-Step Digital Twin Implementation Examples*

---

## HPC for Digital Twin Analysis and Simulation

Implementing cloud-based simulations and predictive analytics requires GPU-accelerated data analysis. Since cloud services are self-service, selecting the appropriate GPU for specific use cases is critical for cost-efficiency. Azure provides a diverse range of **NVIDIA-powered HPC** (High-Performance Computing) services, allowing users to distinguish between GPUs optimized for AI training versus those optimized for inference.

![Figure 6 - Diverse Azure HPC Cloud Services](media/image7.png)

> *Figure 6 – Diverse Azure HPC Cloud Services Tailored to User Requirements*

---

## Conclusion

While many domestic companies are considering Digital Twins, establishing a clear direction remains challenging. Implementing a digital twin across the entire manufacturing process is a pioneering endeavor. Since innovation often involves trial and error, cloud services offer the ideal platform—providing the flexibility to pivot quickly and the rich infrastructure needed to build high-quality systems.

In the modern era, global economic policies like the **U.S. Inflation Reduction Act (IRA)** are reshaping the manufacturing landscape. For Korean companies expanding into eco-friendly sectors, realigning supply chains and manufacturing capabilities is essential for U.S. exports. Utilizing Digital Twins to plan and verify new local facilities in a virtual environment will serve as a vital competitive edge in responding swiftly to these market shifts.
