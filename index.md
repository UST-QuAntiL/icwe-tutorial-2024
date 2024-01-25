---
title: About
layout: default

navigation_weight: 1
---

This website hosts the material of the tutorial "Quantum Service-oriented Computing: A Practical Introduction to Quantum Web Services and Quantum Workflows", which will be held in Tampere (Finland) during the 2024 edition of the [International Conference on Web Engineering (ICWE)](https://icwe2024.webengineering.org/).

# Abstract

Quantum applications are hybrid and require quantum and classical programs.
Similar to classical applications, they can benefit from modularity, maintainability, and reusability.
This can be achieved by implementing the different functionalities of quantum applications as independent web services.
In this tutorial, we provide an overview of concepts to develop and execute quantum applications based on the paradigm of service-oriented computing.
This includes the development of quantum web services and corresponding OpenAPI specifications.
Further, these services are orchestrated using quantum workflows to achieve robustness, scalability, and reliability.
Thereby, concepts and tools for their modeling, execution, and monitoring are introduced and practically applied.

# Motivation 

Quantum computers provide a computational advantage over classical computers by exploiting quantum mechanical phenomena, such as entanglement and superposition [[4]](#4).
However, quantum computers won't replace classical computers but rather serve as co-processors for specific problems, as they are not suitable for many traditional tasks, such as data persistence [[6]](#6).
Hence, hybrid quantum applications require the integration of classical and quantum programs.
These applications can benefit from classical software engineering principles, such as modularization and separation of concerns [[1]](#1).
In particular, service-based access of quantum computers is suitable, as they are typically provided via the cloud [[3]](#3).
However, the development of quantum web services requires expert knowledge of quantum programming and hardware.
To tackle this issue, an approach for the automated generation of quantum web services using OpenAPI specifications, as well as their automated deployment, has been presented [[2]](#2).
Since hybrid quantum applications typically comprise many of these services, they must be orchestrated, i.e., the control and data flow between them must be defined [[5]](#5).
Due to advantages, such as transaction processing, reliability, and robustness, workflows are a suitable technology for this orchestration.

# Intended Audience

Attendees of this tutorial do not require any previous knowledge of quantum computing or quantum software engineering.
The tutorial provides basic knowledge about designing, developing, deploying, and executing hybrid quantum applications.
Therefore, it teaches attendees to develop and deploy quantum web services, as well as how to orchestrate them utilizing quantum workflows.

# Technical Requirements

The practical part of the tutorial requires a laptop with Docker and Docker-Compose installed.
Further, to employ state-of-the-art quantum computers for executing the modeled hybrid quantum applications, an IBMQ account is needed, which can be created free of charge.
Alternatively, a local simulator can be used for executing the quantum circuits, as described in the tutorial materials.

# Learning Goals

Attendees will have obtained knowledge on:

- Fundamentals about quantum computing and quantum software engineering.
- How to develop quantum web services utilizing OpenAPI specifications.
- Modular development of hybrid quantum applications, their orchestration using workflows, and automatic deployment using TOSCA.
- How to observe and analyze quantum workflows using process views in a unified and user-specific manner.

## References

<a id="1">[1]</a> Beisel, M., Barzen, J., Garhofer, S., Leymann, F., Truger, F., Weder, B., Yussupov, V.: **Quokka: A Service Ecosystem for Workflow-Based Execution of Variational Quantum Algorithms.** In: Service-Oriented Computing – ICSOC 2022 Workshops. Springer (2023)

<a id="2">[2]</a> TODO

<a id="3">[3]</a> TODO

<a id="4">[4]</a> Nielsen, M.A., Chuang, I.: **Quantum Computation and Quantum Information.** AAPT (2010)

<a id="5">[5]</a> Weder, B., Breitenbücher, U., Leymann, F., Wild, K.: **Integrating Quantum Computing into Workflow Modeling and Execution.** In: Proceedings of the 13th IEEE/ACM International Conference on Utility and Cloud Computing (UCC). pp. 279–291. IEEE Computer Society (2020)

<a id="6">[6]</a> Weder, B., Barzen, J., Leymann, F., Vietz, D.: **Quantum Software Development Lifecycle**, pp. 61–83. Springer (2022)  
