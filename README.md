# Arthenyx — Autonomous Cost Intelligence Platform
Arthenyx is a multi-agent AI system designed to bridge the gap between reactive monitoring and autonomous financial operations. It detects cost risks before they manifest in billing dashboards by analyzing the "narrative" of your infrastructure.

🚀 The Core Innovation: Narrative Fragility Index (NFI)
Traditional FinOps is reactive—you find out you spent too much after the bill arrives. Arthenyx computes the Narrative Fragility Index (NFI):

Structured Data: Cloud usage logs and billing metrics.

Unstructured Signals: DevOps reports, deployment narratives, and resource logs.

The Result: An early warning signal that identifies financial inefficiencies before the "spike" happens.

🤖 System Architecture
Arthenyx operates through a specialized chain of AI agents:

IngestionAgent: Aggregates logs and narrative reports.

NarrativeAnalysisAgent: Parses unstructured text for risk signals.

DriftDetectionAgent (NFI Engine): Computes the risk score.

DecisionAgent: Evaluates root causes and determines corrective paths.

ActionAgent: Executes autonomous fixes or prepares human-in-the-loop escalations.

AuditAgent: Maintains a transparent, immutable log of financial impact.

✨ Features
Predictive Risk Detection: Move beyond simple threshold alerts.

Multi-Agent Pipeline: Autonomous reasoning for complex cloud environments.

Real-time Simulation Dashboard: High-fidelity Glassmorphism UI for monitoring NFI trends.

Financial Impact Logging: Every action is mapped to potential savings (e.g., ₹/hr).

Human-in-the-loop: Configurable thresholds for autonomous vs. manual execution.

🛠️ Tech Stack
Component	Technologies
Backend	Python 3, Dataclasses, Agentic Logic
Frontend	React, Lovable, Framer Motion (Animations)
Design	Glassmorphism, Tailwind CSS
📂 Project Structure
Plaintext
Arthenyx/
├── BackendLogic/
│   └── Main_Agentic.py         # Core multi-agent logic & NFI engine
├── SimulationFrontend/
│   ├── src/                    # React components & Framer Motion logic
│   └── package.json
└── README.md
🏃 Getting Started
Note: The Frontend is a high-fidelity simulation; the Backend demonstrates the core decision-making logic.

1. Backend Setup (Python)
Bash
cd BackendLogic
python Main_Agentic.py
Expected Output: You will see the agentic pipeline execute in the terminal, showing NFI computation, decision logs, and projected savings (e.g., Savings: ₹1,040,400/mo).

2. Frontend Setup (React UI)
Bash
cd SimulationFrontend
npm install
npm run dev
Navigate to http://localhost:8080/ to view the real-time simulation dashboard.

🎯 Demo Scenarios
Cloud Over-provisioning: Detects demand slowdown → Scaledown triggered.

Vendor Duplication: Identifies redundant SaaS tools → Consolidation recommended.

SLA Breach Risk: Detects operational bottlenecks → Task reassignment executed.

🚧 Roadmap & Limitations
Mocked APIs: Current version uses simulated cloud and billing APIs for demonstration.

Future Integration: Plans to connect directly to AWS Cost Explorer and SaaS billing endpoints.

Persistence: Move from in-memory audit logs to a persistent database (PostgreSQL).

Author: Aditi Rathore | Built for Hackathon v1.0

Would you like me to generate a specific "How it Works" section for the NFI math to make the technical depth even more impressive?
