# Federated Fairness-Aware Cache Allocation in Multi-Tenant Edge Computing

This repository contains the full implementation and experimental results for our project on privacy-preserving and fairness-aware cache allocation in multi-tenant edge computing.  
The work extends the model-based reinforcement learning (MB-RL) method of *Ben-Ameur et al., IEEE TCC 2025* by incorporating federated learning (FL) with fairness-aware aggregation.

##  Overview

Multi-tenant edge systems must allocate limited cache space among tenants with widely varying request patterns.  
Traditional online RL approaches—such as MB-RL—require centralized access to raw request traces, which is often not feasible due to:

- Privacy constraints  
- Distributed edge nodes  
- Bandwidth limitations  
- Highly imbalanced tenant presence across sites  

To address these challenges, this project implements a federated reinforcement learning framework, where edge nodes train locally and share only model updates.  
A fairness term is added during aggregation to prevent high-demand tenants from dominating the cache.




