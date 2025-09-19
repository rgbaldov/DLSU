# Automated Aircraft Damage Detection and Assessment using Drone-based Computer Vision and Digital Twin Technology

Student Researchers: **Matthew Edward K. Chua, Angelo V. Diaz, Joshua Emmanuel U. Legaspi, Reevee Kacy A. Lo, Gino C. Sangalang**

Advisers: **[Renann G. Baldovino, PhD](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/manufacturing-engineering-management/faculty-profile/renann-baldovino/) & [Jerahmeel K. Coching. MSc](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/manufacturing-engineering-management/faculty-profile/jerahmeel-coching/)**

**[Department of Manufacturing Engineering and Management, De La Salle University (DLSU)](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/manufacturing-engineering-management/)**  

## Research Collaboration:
<p align="center">
  <img src="https://github.com/user-attachments/assets/275c4dbe-8e4b-4199-ae1a-4286ce06b8d1" alt="DLSU" width="150" height="150"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/ee4a09dc-f61f-4ec0-b099-e2e33af5e75a" alt="Cebu Pacific" width="150" height="150"/>
</p>

## Main Objective:
To develop a drone-based system with depth cameras and computer vision for automated aircraft surface damage assessment, integrated with digital twin technology for real-time monitoring and predictive maintenance

## Key Features:
- **Drone-Based Inspection:** Autonomous flights for fast and efficient aircraft surface coverage.  
- **Depth Cameras:** High-resolution 3D imaging for accurate damage detection and sizing.  
- **Computer Vision:** Automated identification of dents, cracks, scratches, and corrosion.  
- **Digital Twin:** Virtual aircraft model updated with real-time inspection data.  
- **Reporting:** Maintenance reports to support decision-making and compliance.  

## Scope and Limitations:
### Scope  
- Develop a drone-based aircraft inspection system using depth cameras, computer vision, and digital twin technology for surface damage detection.  
- Focus on Airbus A320 aircraft as the baseline model for testing and validation.  
- Limit inspections to external surfaces (fuselage and wings) for detecting dents, cracks, corrosion, and visible damage.  
- Design and test a prototype system consisting of a drone platform, camera sensors, and software algorithms for image capture, damage detection, and 3D visualization.  
- Explore integration with digital twin models for aircraft condition monitoring and provide basic reporting for quality control.  

### Limitations  
- System testing restricted to Airbus A320 models; other aircraft types not included.  
- Inspections limited to external surfaces only; no internal components or avionics covered.  
- Real-world implementation with Cebu Pacific subject to regulatory approval; airport testing may be restricted.  
- Prototype focused on proof-of-concept accuracy and reliability, not full-scale commercial deployment.  
- Environmental factors (e.g., extreme weather, poor lighting, crowded conditions) excluded from initial testing.  
- No full integration with airline maintenance software (e.g., AMOS, TRAX); only basic inspection data outputs provided.  

## Phase 1 (Capstone): Drone-Based Aircraft Damage Detection using Computer Vision (_6 mos_) 
**Objectives:**  
- Develop and integrate a drone-mounted imaging system capable of capturing high-resolution aircraft surface images.  
- Train and optimize computer vision models for automated detection and classification of structural damage (e.g., dents, cracks, corrosion).  
- Validate detection accuracy against manual inspection results to ensure reliability.  
- Establish a real-time data transfer pipeline between drones and ground systems for immediate assessment.  

```mermaid
flowchart TB
    A[Start] --> B[Drone Flight Around Aircraft]
    B --> C[Capture High-Resolution Images with Depth Cameras]
    C --> D[Preprocess Images (Filtering & Alignment)]
    D --> E[Computer Vision Analysis]
    E --> F{Damage Detected?}
    F -- Yes --> G[Classify Damage <br/>(Dent, Crack, Corrosion, etc.)]
    G --> H[Store Results & Generate Alerts]
    F -- No --> I[Continue Inspection]
    H --> J[Transmit Data to Ground System]
    I --> J
    J --> K[End of Phase 1]

---

## Phase 2 (Thesis): Digital Twin–Based Damage Assessment and Visualization (_1 yr_)
**Objectives:**  
- Create a digital twin model of the aircraft to map detected damages onto a 3D representation.  
- Simulate the potential structural and operational impact of identified damages within the digital twin environment.  
- Develop a user-friendly dashboard for maintenance teams to visualize and prioritize detected damages.  
- Integrate predictive maintenance insights to support decision-making and reduce aircraft downtime.  
