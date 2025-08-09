# FlowSwarm Project Visualization

## Project Overview Diagram

```mermaid
graph TB
    A[FlowSwarm Project] --> B[Phase 1: Theory]
    A --> C[Phase 2: VR Lab]
    A --> D[Phase 3: Bio-Robotics]
    
    B --> B1[Vicsek Model Extension]
    B --> B2[Flow Integration]
    B --> B3[Multi-Scale Modeling]
    
    C --> C1[VR System Design]
    C --> C2[Flow Visualization]
    C --> C3[Haptic Feedback]
    
    D --> D1[Mudskipper Robots]
    D --> D2[Flow Sensing]
    D --> D3[Swarm Coordination]
    
    B3 --> E[Collective Behavior Understanding]
    C3 --> E
    D3 --> E
```

## Timeline Visualization

```mermaid
gantt
    title FlowSwarm 24-Month Timeline
    dateFormat YYYY-MM-DD
    section WP1: Theory
    Literature Review     :2025-01-01, 3M
    Model Development     :2025-02-01, 4M
    VR Design            :2025-04-01, 2M
    
    section WP2: Setup
    VR Construction      :2025-07-01, 4M
    Robot Development    :2025-08-01, 3M
    Sensor Integration   :2025-10-01, 2M
    
    section WP3: Data
    VR Experiments       :2026-01-01, 4M
    Robot Testing        :2026-02-01, 3M
    Flow Characterization:2026-03-01, 2M
    
    section WP4: Analysis
    Model Validation     :2026-07-01, 4M
    Cross-validation     :2026-09-01, 2M
    Publication Prep     :2026-10-01, 2M
```

## Conceptual Framework

```mermaid
flowchart LR
    A[Individual Agent] --> B{Sensory Integration}
    B --> C[Visual Cues]
    B --> D[Flow Information]
    B --> E[Social Signals]
    
    C --> F[Decision Making]
    D --> F
    E --> F
    
    F --> G[Movement Action]
    G --> H[Group Dynamics]
    
    H --> I[Emergent Patterns]
    I --> J[Collective Behavior]
    
    K[Large-Scale Flow] --> D
    L[Turbulence] --> D
    M[Currents/Winds] --> D
```

## System Architecture

```mermaid
graph TB
    subgraph "VR Environment"
        VR1[Flow Visualization]
        VR2[Haptic Feedback]
        VR3[Multi-Agent Interface]
    end
    
    subgraph "Physical Testing"
        P1[Wind/Water Tunnels]
        P2[Robotic Swarms]
        P3[Flow Sensors]
    end
    
    subgraph "Computational Models"
        M1[Extended Vicsek Model]
        M2[Flow-Behavior Integration]
        M3[Collective Intelligence]
    end
    
    VR1 <--> P1
    VR2 <--> P3
    VR3 <--> P2
    
    P1 --> M1
    P2 --> M2
    P3 --> M3
    
    M1 --> VR1
    M2 --> VR2
    M3 --> VR3
```

## Innovation Mapping

```mermaid
mindmap
  root)FlowSwarm Innovation(
    Scientific
      Multi-sensory Integration
      Cognitive Flow Models
      Cross-scale Dynamics
    Technological
      VR-Flow Systems
      Amphibious Swarms
      Flow-aware AI
    Methodological
      Immersive Experiments
      Bio-inspired Validation
      Real-time Flow Sensing
    Applications
      Marine Conservation
      Drone Coordination
      Disaster Response
```

## Impact Visualization

```mermaid
graph LR
    A[FlowSwarm Research] --> B[Scientific Impact]
    A --> C[Technological Impact]
    A --> D[Societal Impact]
    
    B --> B1[Fundamental Understanding]
    B --> B2[New Paradigms]
    B --> B3[Interdisciplinary Bridge]
    
    C --> C1[VR Technology]
    C --> C2[Robotic Systems]
    C --> C3[Flow-aware AI]
    
    D --> D1[Conservation Applications]
    D --> D2[Disaster Response]
    D --> D3[Autonomous Systems]
    
    B1 --> E[Publications]
    B2 --> E
    C1 --> F[Patents/IP]
    C2 --> F
    D1 --> G[Policy/Standards]
    D2 --> G
```

## Research Integration

```mermaid
graph TB
    subgraph "Current Research"
        CR1[Mudskipper Robots]
        CR2[DARPA Projects]
        CR3[Air-Water Transitions]
    end
    
    subgraph "Literature Base"
        LB1[Sayin et al. 2025]
        LB2[Vicsek Model]
        LB3[Collective Behavior]
    end
    
    subgraph "FlowSwarm"
        FS1[Flow-Integrated Models]
        FS2[VR Experiments]
        FS3[Bio-inspired Swarms]
    end
    
    CR1 --> FS3
    CR2 --> FS2
    CR3 --> FS1
    
    LB1 --> FS1
    LB2 --> FS1
    LB3 --> FS2
    
    FS1 --> O[Outcomes]
    FS2 --> O
    FS3 --> O
```