  # DiveLikeAHuman

 ## 1. Project Overview
 DiveLikeAHuman targets underwater autonomous systems and aims to build a human-like decision-making
 framework for navigation and obstacle avoidance in complex underwater environments. The framework
 focuses on behavior selection and trajectory guidance under safety and efficiency constraints.

 ## 2. Core Functions

 ### 2.1 Environmental Representation and Situation Modeling
 - Structuring surrounding targets and obstacles into a unified scene description
 - Distinguishing static obstacles and dynamic entities, and extracting key interaction features
 - Focusing on a limited number of high-priority entities to reduce decision complexity

 ### 2.2 Behavior Evaluation and Action Selection
 - Joint evaluation of a set of basic action modes with safety–efficiency trade-offs
 - Producing an action preference distribution and a recommended action
 - Providing decision intents and explanatory information to support analysis and interpretability
 studies

 ### 2.3 Control Guidance and System Coordination
 - Mapping high-level decisions into constraints and guidance signals usable by lower-level controllers
 - Supporting integration with existing simulation environments and control systems
 - Enabling closed-loop simulations and comparative experiments for different decision schemes

 ## 3. Typical Application Scenarios
 - Autonomous navigation and obstacle avoidance research for underwater robots and AUVs
 - Modeling of multi-agent interaction and cooperative behavior in underwater settings
 - Prototyping and benchmarking decision algorithms

 ## 4. Key Characteristics
 - Specialized design for multi-target, multi-obstacle underwater scenarios
 - Emphasis on decision process interpretability and analysis-friendliness
 - Modular architecture, facilitating extension of perception, decision, and control components