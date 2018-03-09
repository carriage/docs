# Documentation
Carriage is an open-source, decentralized platform for EV charging that helps get electric vehicle charging infrastructure installed where drivers need it, enforceably reserved when they want to use them, and repaired when they have issues. Our goal is to accelerate the adoption of electric and autonomous vehicle by building tools that support the infrastructure the industry needs.

# Overview

## Glossary
**Platform**: The overall configuration of the Carriage network that entails the interaction between the mobile application, web application, and blockchain.  
- *Roadmap*: The platform timeline and vision is laid out in the platform roadmap.

**Component**: The individual project folders that define the different parts of the Carriage platform. Taken together, these provide the essential functions of the platform: 
1) Carriage RNA: the mobile application for drivers
2) Carriage DNA: the blockchain protocol that is consists of 

    (A) Project financing  
    (C) Payments  
    (G) Reservations  
    (T) Maintenance  
3) Carriage Protein: the web application for building owners, hardware manufacturers, automotive OEMs, contractors, utilities and other stakeholders.
4) Carriage Carb: the statistical model for the optimal placement of charging stations to be used as a null hypothesis for the driver demand model.
5) Carriage Lipid: the V2G service to allow for power grid optimization using spare vehicle storage capacity.
- *FeatureMap*: Each project folder has a list of features mapped against the overall platform roadmap. The featuremap is a list of all features specific to that component, ordered according to the overall roadmap.

**Feature**: The distinct attributes that make up a component.

**Issue**: The lowest level aspects of a feature that can be discretized and worked on individually.


## Roadmap 
The overall platform vision and roadmap is housed in this folder in the roadmap.md file. The roadmap is broken down into discrete milestones, which consist of progress made across the features in component packages (RNA, DNA, Carriage). Each component has a featuremap whose milestones map to this higher level roadmap. Issues in each project folder are the lowest level, discrete pieces of the features needed to execute the platform roadmap. Visually: issues -> features -> components -> plaform.

## Components
Carriage consists of a protocol layer of smart contracts (Carriage DNA) that are built on top of the Ethereum blockchain that function at each stage of the lifecycle of a charging station: initial project financing, ongoing use (payments and reservations), and maintenance & repairs.

On top of these protocols is an application front-end layer for drivers and charging station owners. The mobile application for drivers is the Carriage RNA, and the web application for station owners is the Carriage UI.

## Repositories
- **carriage-dna**: Back-end blockchain server and smart contracts for protocols. (Solidity/Truffle)  
- **carriage-rna**: Mobile application for drivers (Javascript/React-Native)  
- **carriage**: Web application for building owners (Javascript/React)  


