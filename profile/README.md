# FledgePower - Power systems protocols translation gateway based on Fledge

## Project Overview

FledgePOWER is a multi-protocol translation gateway for power systems based on the industrial IoT LF Edge project Fledge.

As power systems transform to include increasing onboarding of renewables, electric vehicles, assets at the edge, or behind the meter, network operators must be able to monitor and interact with substation equipment where a high-volume of data is exchanged with a high-velocity of change. These exchanges require real-time, efficient, robust, and secure communications.

Telecontrol protocols are used at many levels of the system: locally, at various connection nodes of the network, at a central level, and at the interface with network operations. Typically, the proliferation of protocols do not share the same specifications, but they often are handling similar data. Implementing new protocols is costly, can create technical debt, and is time-consuming. To manage this heterogeneous environment, the multi-protocol and evolving protocol phenomena lead operators to run deprecated protocols, as a legacy, for decades. With the speed of change increasing, network operations become increasingly complex, less flexible, and ultimately are expensive to operate. Having the ability to abstract this complexity of protocols with FledgePOWER will offer power system network operators new tools in a rapidly transforming environment.

FledgePOWER solves the problem of multiple protocols by providing the industry with a flexible, lightweight, industrial-grade, open source gateway that embeds Fledge (LF EDGE). Additionally, FledgePOWER provides a toolbox for simulation, data configuration, and checking focused uniquely on power systems’ protocols translation and power systems’ use cases. 

FledgePOWER is a cross foundation collaboration between LF Edge and LF Energy that ensures strong cooperative governance and technical alignment between the two communities.

Moreover, FledgePOWER aims to build and grow a community of end-users, developers, utilities, and other players to collaborate to solve current and future challenges in the energy space.


## Project Details

Build a gateway to meet the following requirements:

- lightweight: it can run on small computers with constrained resources
- extensible: new protocols need → new plugin
- modular: each part is a small consistent brick that runs as a micro service
- flexible: install only what you need where you need it
- scalable: it can be deployed on a single instance or scale to thousands of sites
- secured: it uses state of the art secured techniques and protocols
- interoperable: generic interface model enables integration with heterogeneous legacy or future products and systems

## Contributing

Interested in contributing? Please read carefully the [CONTRIBUTING guidelines](https://github.com/fledge-power/contributing/blob/main/CONTRIBUTING.md).

You can also read the project's [WIKI](https://wiki.lfenergy.org/display/FLED/FledgePower) for more information about the design and architecture.

## SONAR dashboard

You can check the project's [SONAR dashboard](https://sonarcloud.io/organizations/fledge-power/projects) 

## OpenSSF Best Practices
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/5969/badge)](https://bestpractices.coreinfrastructure.org/projects/5969)

## CI Status
### fledge-north-iec104
[![CI](https://github.com/fledge-power/fledge-north-iec104/actions/workflows/ci.yml/badge.svg)](https://github.com/fledge-power/fledge-north-iec104/actions/workflows/ci.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=fledge-power_fledge-north-iec104&metric=alert_status)](https://sonarcloud.io/dashboard?id=fledge-power_fledge-north-iec104)
### fledge-south-iec104
[![CI](https://github.com/fledge-power/fledge-south-iec104/actions/workflows/ci.yml/badge.svg)](https://github.com/fledge-power/fledge-south-iec104/actions/workflows/ci.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=fledge-power_fledge-south-iec104&metric=alert_status)](https://sonarcloud.io/dashboard?id=fledge-power_fledge-south-iec104)
### fledge-north-s2opcua
[![CI](https://github.com/fledge-power/fledge-north-s2opcua/actions/workflows/ci.yml/badge.svg)](https://github.com/fledge-power/fledge-north-s2opcua/actions/workflows/ci.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=fledge-power_fledge-north-s2opcua&metric=alert_status)](https://sonarcloud.io/dashboard?id=fledge-power_fledge-north-s2opcua)
### fledgepower-filter-pivottoopcua
[![CI](https://github.com/fledge-power/fledgepower-filter-pivottoopcua/actions/workflows/ci.yml/badge.svg)](https://github.com/fledge-power/fledgepower-filter-pivottoopcua/actions/workflows/ci.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=fledge-power_fledgepower-filter-pivottoopcua&metric=alert_status)](https://sonarcloud.io/dashboard?id=fledge-power_fledgepower-filter-pivottoopcua)
### fledge-south-iec61850
[![CI](https://github.com/fledge-power/fledge-south-iec61850/actions/workflows/ci.yml/badge.svg)](https://github.com/fledge-power/fledge-south-iec61850/actions/workflows/ci.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=fledge-power_fledge-south-iec61850&metric=alert_status)](https://sonarcloud.io/dashboard?id=fledge-power_fledge-south-iec61850)
