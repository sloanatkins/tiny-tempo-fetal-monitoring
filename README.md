# Tiny Tempo  
*A Wearable-Integrated Fetal Monitoring Mobile Health Application*

## Overview

Tiny Tempo is a conceptual mobile health application designed to support late-stage pregnancy monitoring through wearable-integrated data collection and intuitive visualization.

The system provides expecting parents with real-time insights into fetal heart rate, movement, and contraction patterns between prenatal appointments, helping reduce anxiety while presenting clear, educational summaries of health data.

This project was developed for **CSC431 – Introduction to Software Engineering** at the University of Miami.

---

## The Problem

Prenatal appointments are typically scheduled every four weeks. During this time, expecting parents—especially those with high-risk pregnancies—have no accessible way to monitor fetal health between visits.

Existing alternatives:
- Clinical in-office visits only  
- Physician-supervised remote monitoring systems  
- Limited independent-use wearable solutions  

Tiny Tempo addresses the gap between clinical-grade systems and parent-friendly monitoring technology.

---

## Proposed Solution

Tiny Tempo combines:

- A conceptual wearable belly band with sensors  
- A mobile application for visualization and tracking  
- Secure backend infrastructure for data storage and analysis  

The system prioritizes:

- Reassurance over diagnostics  
- Clear visual summaries  
- Privacy and secure data handling  
- Ethical design for safety-conscious development  

---

## Core Features

### Heart Rate Monitoring
- Periodic Doppler-style readings (not constant monitoring)  
- Displays a safe range rather than a single number  
- Soft heartbeat playback  
- Trend tracking over time  

### Baby Movement Detection
- Motion-based kick counter  
- Daily movement summaries  
- Pattern visualization  

### Braxton Hicks Detection
- Pattern recognition for irregular contractions  
- Differentiates from active labor  
- Reduces unnecessary anxiety  

### Labor Contraction Tracking
- Tracks duration and frequency  
- Manual confirmation from parent  
- Contraction timer  
- Alert when patterns indicate possible labor  

---

## System Architecture

**Frontend**
- React (JavaScript)  
- Responsive UI for data visualization  
- Designed using Figma prototypes  

**Backend**
- Python (Flask or FastAPI)  
- RESTful API endpoints  
- Data processing and pattern recognition  

**Database**
- Secure cloud-hosted database  
- HIPAA-aware infrastructure (conceptual planning)  

**Version Control**
- GitHub Team workflow  
- Branch-based development  

---

## Development Timeline (12 Weeks)

| Phase | Duration |
|-------|----------|
| Conceptual Design | 2 weeks |
| UI/UX & Architecture Design | 3 weeks |
| Implementation & Integration | 4 weeks |
| Testing & Validation | 2 weeks |
| Deployment Planning | 1 week |

---

## My Role

- System architecture planning  
- Backend requirements documentation  
- Software Requirements Specification (SRS)  
- Software Architecture Specification (SAS)  
- Technical documentation consistency  

This project strengthened my experience in:

- Safety-conscious system design  
- Health-tech architecture planning  
- Requirement documentation  
- Team-based version control workflows  

---

## Key Software Engineering Concepts Demonstrated

- Requirements engineering  
- Architectural design documentation  
- API design and data flow modeling  
- Iterative development  
- Validation and testing planning  
- Cost estimation  
- Ethical and security considerations in health systems  

---

## Repository Structure

```
tiny-tempo-fetal-monitoring/
│
├── README.md
├── docs/
│   ├── Project_Proposal.pdf
│   ├── SRS.pdf
│   ├── SAS.pdf
│
├── frontend/
│
├── backend/
│
└── diagrams/
```

---

## Future Improvements

- Real wearable hardware integration  
- FDA-compliant development process  
- AI-assisted anomaly detection  
- Secure physician dashboard portal  
- Cross-platform native mobile app  

---

## Disclaimer

Tiny Tempo is a conceptual academic project and is not a certified medical device. It is intended for educational and software engineering demonstration purposes only.
