AI Agents Assignment – Smart Manufacturing Case Study
📌 Project Overview

This repository contains the complete submission for the AI Agents Assignment, focusing on the design, application, and simulation of AI Agents within a smart manufacturing context.

The project combines:

A written PDF report (theoretical analysis + case study)

A practical AI Agent simulation built using n8n

This README file, which explains how the simulation complements the written analysis

The case study centers on AutoParts Inc., a mid-sized automotive parts manufacturer facing quality issues, machine downtime, labor challenges, and increased customization demands.

📂 Repository Structure
├── AI_Agents_Assignment.pdf
├── simulation/
│   └── AutoParts AI Agent Simulation – Smart Manufacturing.json
└── README.md

🎯 Assignment Objectives

This submission demonstrates:

Understanding of AI Agent frameworks and concepts

Application of multi-agent systems to a real-world manufacturing problem

Consideration of business impact, ROI, and ethics

Practical simulation of agent coordination using n8n, as required by the assignment instructions

🏭 Case Study Summary: AutoParts Inc.

AutoParts Inc. is experiencing:

~15% defect rate in precision components

Unpredictable machine downtime

Rising labor costs and retention issues

Customer pressure for faster, customized deliveries

To address these challenges, a coordinated AI Agent system was proposed and simulated.

Full analysis and recommendations are provided in the PDF.

🤖 AI Agent Architecture (Simulated)

The solution consists of three core AI Agents, each represented by a dedicated node in the n8n workflow:

1. Quality Control Agent

Evaluates production defect rates

Triggers corrective actions when defects exceed acceptable thresholds

2. Predictive Maintenance Agent

Analyzes machine health indicators (temperature and vibration)

Determines whether proactive maintenance is required

3. Production Planning Agent

Adjusts schedules and priorities based on quality and maintenance outcomes

Enables customization handling for high-priority orders

A human-in-the-loop notification step ensures managerial oversight.

🔄 n8n Workflow Simulation
Purpose of the Simulation

The n8n workflow serves as a conceptual and functional simulation of how AI Agents can:

React to production events

Make autonomous decisions

Coordinate actions across manufacturing operations

Escalate decisions to humans when necessary

This fulfills the assignment requirement to “simulate your solution on n8n or make.com.”

🧩 Workflow Logic (Mapped to Actual Nodes)

The implemented workflow follows this sequence:

Manual Trigger
Simulates the completion of a production batch.

Simulated Production Data (Set Node)
Generates mock factory data:

defect_rate

machine_temperature

vibration_level

order_priority

Quality Control Agent (IF Node)

Condition: defect_rate > 15

Represents automated defect detection logic.

Predictive Maintenance Agent (IF Node)

Conditions:

machine_temperature > 80

vibration_level > 6

Uses OR logic to simulate failure prediction.

Production Planning Agent (Set Node)

Adjusts:

Production schedule

Order priority

Custom order handling

Notify Operations Manager (NoOp Node)

Represents human oversight and ethical safeguards.

🔗 Simulation File

The n8n workflow used for this simulation is included in the repository and can be imported directly into n8n.

📁 Workflow File:
simulation/AutoParts AI Agent Simulation – Smart Manufacturing.json

⚖️ Scope and Assumptions

The simulation uses mock data rather than live factory sensors

Decision logic is rule-based to represent AI Agent reasoning

The focus is on architecture, orchestration, and decision flow

Human oversight is intentionally preserved to address ethical considerations

This scope aligns with academic expectations for applied AI Agent demonstrations.

✅ Alignment With Assignment Requirements

✔ AI Agent concepts and frameworks analyzed
✔ Real-world manufacturing case study addressed
✔ Multiple AI Agent types defined and coordinated
✔ Business impact and risks considered
✔ Simulation implemented using n8n
✔ Simulation link/file appended to GitHub repository

🚀 Final Note

This project demonstrates how AI Agents can function as collaborative decision-makers rather than isolated automation tools. By pairing theoretical analysis with a practical simulation, the submission highlights both conceptual depth and applied understanding of AI Agent systems in smart manufacturing.