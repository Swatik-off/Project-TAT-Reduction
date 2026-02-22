# Project-TAT-Reduction
Turn Around Time Optimization Project at HCL
🚚 Reduction in Turn Around Time (TAT)
Supply Chain Process Optimization Project
📌 Project Overview

This project focuses on reducing Turn Around Time (TAT) for inbound material handling in a manufacturing environment.

Turn Around Time refers to the total time taken from vehicle arrival at the gate to exit after unloading and inspection.

The study identifies operational bottlenecks in:

Gate Entry Process

Quality Inspection

Material Handling

Store Operations

Inventory Documentation

The objective was to apply Supply Chain Management (SCM) principles and improve process efficiency, resource utilization, and coordination between departments.

🎯 Problem Statement

High TAT was causing:

Vendor delays

Truck congestion

Increased waiting cost

Inefficient manpower utilization

Operational imbalance between Quality and Store

The existing system had:

Multiple manual verification steps

Unbalanced inspection workload

Limited material handling equipment

Poor process synchronization between PPC, Store, and Quality

FIFO followed without considering priority optimization

🔍 Process Breakdown (As-Is Process)

The inbound process included:

Vehicle arrival & reporting

Document verification

Gate entry slip generation

SAP entry

Docket/SRR stamping

Quality inspection

Unloading

Counting

Stacking

Exit

This resulted in:

Redundant documentation steps

Manual intervention errors

Unbalanced inspection time

High waiting during peak hours (after 6 PM)

📊 Root Cause Analysis

Using Process Mapping and Operational Flow Analysis, the following bottlenecks were identified:

1️⃣ Quality Inspection Bottleneck

No inspection before 11:30 AM

Only 1 skilled inspector available during peak time

Rush after 6 PM

Inefficient FIFO usage without prioritization logic

2️⃣ Gate Entry Redundancy

Multiple verification layers

Manual SAP entry

Separate stamping processes

3️⃣ Store Constraints

Insufficient trolleys (Material Handling Equipment issue)

Blocked gangways (Poor Warehouse Layout Optimization)

MPQ & BPR mismatch (Lack of Planning Synchronization)

🛠 Supply Chain Methods Applied

This project applies the following Supply Chain & Operations Management concepts:

✅ Process Re-engineering

Clubbing multiple gate steps into one automated QR-based document verification.

✅ Capacity Planning

Reallocating manpower across shifts:

1 person (9 AM – 2 PM)

2 persons (2 PM – 6 PM)

3+ persons after 6 PM (peak load)

✅ Workload Balancing Model

Inspection categories classified based on:

High Quantity / Low Variety

Low Quantity / High Variety

Medium combinations

Then distributed using:

Max Time + Min Time pairing logic (A+F, B+E, C+D)

This improves:

Counter utilization

Average inspection time

Throughput efficiency

✅ Lean Principles

Removal of non-value-added steps

Reduction of motion waste

Elimination of waiting time

✅ Digitalization & Automation

QR-based document scanning

Automated SAP entry

ASN (Advanced Shipping Notice) system revival

✅ Warehouse Optimization

Introduction of additional trolleys

Clearing gangways

Defined storage handling responsibility

📈 Proposed Improvements
🔹 Gate Optimization

QR-based verification

Automated SAP Integration

Single-point document processing

🔹 Quality Inspection Strategy

Shift-wise manpower planning

Load balancing of inspection categories

Priority-based inspection instead of pure FIFO

🔹 Store & Inventory Alignment

MPQ & MOQ alignment with BPR

Restart ASN system

Better coordination between PPC, SCM, Quality, and Store

📊 Expected Impact
Area	Improvement
Turn Around Time	Significant reduction
Vendor Waiting Cost	Reduced
Process Errors	Minimized
Inspection Throughput	Increased
Resource Utilization	Optimized
Interdepartmental Coordination	Improved
💡 Supply Chain Advantages

This project strengthens the supply chain in the following ways:

🔹 Improves Inbound Logistics Efficiency

Reduces congestion and improves material flow.

🔹 Enhances Operational Visibility

Through digital documentation and ASN implementation.

🔹 Increases Throughput Rate

Balanced inspection counters reduce idle time.

🔹 Reduces Lead Time Variability

Better manpower planning reduces bottleneck delays.

🔹 Supports Lean Supply Chain Strategy

Eliminates waste in:

Waiting

Motion

Over-processing

🔹 Improves Inventory Accuracy

Alignment between MPQ, MOQ, and BPR reduces mismatch.

🧠 Key Supply Chain Concepts Demonstrated

Turn Around Time (TAT) Optimization

Process Mapping

Capacity Planning

Lean Operations

Throughput Maximization

Workload Balancing

Warehouse Layout Efficiency

Digital Supply Chain Integration

Cross-Functional Coordination

Inbound Logistics Optimization

🤝 Cross-Functional Collaboration

This project required coordination between:

Quality Department

Store Operations

Production Planning & Control (PPC)

Supply Chain Management (SCM)

Purchase Department

It highlights the importance of Integrated Supply Chain Decision-Making.

📌 Conclusion

By applying structured Supply Chain Management methodologies, the project successfully identifies and proposes actionable improvements to reduce Turn Around Time.

The approach focuses on:

Eliminating operational inefficiencies

Improving manpower utilization

Enhancing digital integration

Strengthening coordination across departments

This model can be scaled and adapted across manufacturing plants aiming to improve Inbound Logistics Performance and Operational Excellence.
