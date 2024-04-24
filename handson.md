---
title: Hands-On Session
layout: default

navigation_weight: 3
---

# Hands-On Session

TODO

The use case utilizes the following tools:

* [Pattern Atlas](https://github.com/PatternAtlas): TODO.
* [Process View Plugin](https://github.com/UST-QuAntiL/camunda-process-view-plugins): TODO.
* [OpenTOSCA Container](https://github.com/OpenTOSCA/container): A TOSCA-compliant deployment system.
* [Quantum Workflow Modeler](https://github.com/PlanQK/workflow-modeler): A graphical BPMN modeler to define, transform, and deploy quantum workflows.
* [Quokka](https://github.com/UST-QuAntiL/Quokka): A microservice ecosystem enabling a service-based execution of quantum algorithms.
* [Winery](https://github.com/OpenTOSCA/winery): A web-based modeler for TOSCA-based deployment models, which can be attached to activities of quantum workflows to enable their automated deployment in the target environment.

## Setup

The code required for the hands-on session is available [here](https://github.com/UST-QuAntiL/QuantME-UseCases/tree/master/2024-icwe-tutorial).

In case you participate in the tutorial on-side and use one of the provided virtual machines, please only download the workflow model available [here](TODO).
Afterwards, move to [Part 1](#part-1-qaoa-for-maxcut) and use the provided IP to replace the placeholder $IP.

On Windows, you have to activate long paths for Git to enable cloning and pushing to this repository.
Thus, execute the following command:

```
git config --system core.longpaths true
```

Afterwards, clone the repository and navigate to the ``2024-icwe-tutorial`` folder:

```
git clone https://github.com/UST-QuAntiL/QuantME-UseCases.git
cd QuantME-UseCases/2024-icwe-tutorial
```

All components are available via Docker.
Therefore, these components can be started using the Docker-Compose file available [here](https://github.com/UST-QuAntiL/QuantME-UseCases/tree/master/2024-icwe-tutorial/docker):

1. Update the [.env](https://github.com/UST-QuAntiL/QuantME-UseCases/tree/master/2024-icwe-tutorial/docker/.env) file with your settings: 
  * ``PUBLIC_HOSTNAME``: Enter the hostname/IP address of your Docker engine. Do *not* use ``localhost``.
  * ``IBM_ACCESS_TOKEN``: Enter your IBMQ token, which can be retrieved [here](https://quantum.ibm.com/). The token can also be left empty, but then the views described below only display a reduced set of data.

2. Run the Docker-Compose file:
```
cd docker
docker-compose pull
docker-compose up --build
```
3. Wait until all containers are up and running. This may take some minutes.

TODO

## Part 1: QAOA for MaxCut

TODO

## Part 2: Pattern-based Generation of Quantum Workflows

TODO