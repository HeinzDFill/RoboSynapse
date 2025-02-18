# A Unified Perception and Decision-Making Framework for Multi-Agent Robots

## 🛠️ Project Overview

In recent years, multi-agent robotic systems have gained significant attention for applications requiring collaborative task execution, such as search and rescue, autonomous delivery, and surveillance. Traditional frameworks for multi-agent robotics often divide perception and decision-making processes into separate modules, where perception serves as an input to decision-making. However, this disjointed approach can lead to inefficiencies, particularly in dynamic environments where real-time adaptability is crucial. 

This research proposes a **unified framework** that integrates perception and decision-making into a cohesive model, enabling each robot within the multi-agent system to autonomously interpret sensory data and make decisions collaboratively. By leveraging a shared representation of the environment, agents in the proposed framework are able to communicate more effectively, adjust to environmental changes, and coordinate actions without requiring centralized control.

### 🚀 Key Contributions
- 📡 **Integrated Perception and Decision-Making:** Fuses sensory input processing and decision logic into a unified model.
- 🤖 **Decentralized Coordination:** Enables robots to collaborate without relying on a central controller.
- ⚡ **Adaptive Environment Interaction:** Improves responsiveness in dynamic, unpredictable environments.
- 🔍 **Enhanced Communication Efficiency:** Utilizes shared environmental representations to optimize agent communication.
- 📈 **Proven Effectiveness:** Demonstrated improved task completion and resilience against communication failures in both simulations and real-world tests.

---

## 🧠 Framework Architecture

The framework consists of the following core components:

1. **Perception Module:**  
   - Utilizes data from sensors such as LiDAR, cameras, and IMUs.  
   - Preprocesses and normalizes inputs for downstream decision-making.

2. **Decision-Making Module:**  
   - Employs a reinforcement learning-based policy network.  
   - Dynamically adjusts behaviors based on real-time environmental changes.

3. **Communication Protocol:**  
   - Implements a lightweight, peer-to-peer protocol for inter-agent coordination.  
   - Includes mechanisms for data synchronization and conflict resolution.

4. **Task Execution Engine:**  
   - Assigns and monitors task progress across agents.  
   - Supports flexible task allocation and reallocation strategies.

---

## ⚙️ Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/unified-multi-agent-framework.git
    cd unified-multi-agent-framework
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Environment**
    - Ensure necessary sensor inputs (e.g., camera, LiDAR) are properly configured.
    - Modify configuration files in `configs/` to match your hardware setup.

---

## 🛠️ Usage

### 1️⃣ **Run Simulation**
```bash
python main.py --mode simulate
