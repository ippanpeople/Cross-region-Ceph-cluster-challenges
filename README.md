# Cross-region-Ceph-cluster-challenges
Overview

This project aims to evaluate the feasibility of constructing a cross-region Ceph cluster over a wide area network (WAN) using Sakura Cloud. By doing so, we explore the possibility of enabling live migration of instances across geographically distributed regions and examine the challenges encountered throughout the process.

Objectives

	•	Ceph Cluster: Set up a cross-region Ceph cluster over a WAN environment.
	•	Live Migration: Test live migration of instances between regions to ensure seamless operation across distributed infrastructure.
	•	Challenge Exploration: Analyze and document challenges such as latency, network performance, data consistency, and storage redundancy across geographically separated nodes.

Methodology

We utilize Sakura Cloud’s infrastructure to simulate a WAN environment, deploying Ceph clusters across multiple regions. The focus is on testing the viability of live instance migration while maintaining data integrity and high availability in a cross-region setting.

Challenges

	•	Network Latency: Addressing potential issues related to higher latency in cross-region communication.
	•	Data Consistency: Ensuring data integrity and consistency across different regions during migration.
	•	Performance Overhead: Managing the performance impact on storage and network throughput.

Conclusion

The results from this project will provide insights into the practical application of cross-region Ceph clusters, the operational challenges involved, and possible solutions for optimizing live migrations in distributed environments.
