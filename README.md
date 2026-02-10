# PadWasteGuard-Multi-Agent-AI-System-for-Sanitary-Pad-Waste-Detection
Using Google SDK and  Gemini ai models  along with yolo model to detect, analyze, search for location, and  write report to the location based on the level of hazard the waste has caused.

### PadWasteGuard is an AI-powered system designed to detect sanitary pad waste from images and assess its environmental and public health impact in real time. The system integrates YOLOv8 for visual object detection with Google Gemini for contextual analysis, enabling accurate identification of pad waste, associated health hazards, and environmental risks.

### Beyond detection, PadWasteGuard performs location-aware risk assessment, analyzing population exposure, proximity to water sources, and availability of waste-management facilities. It then automatically generates a professional, action-oriented report that highlights danger levels, urgency, and recommended cleanup actions.

### Built with a direct execution pipeline (no async delays), PadWasteGuard delivers immediate results, making it suitable for smart city sanitation, municipal monitoring, environmental research, and public health applications.

## Project Structure
PadWasteGuard/
│
├── Config
│   ├── API keys & model configuration
│
├── WorkingVisionAgent
│   ├── YOLOv8 object detection
│   ├── Gemini image-based waste analysis
│
├── WorkingLocationAgent
│   ├── Location risk assessment
│   ├── Facility & population analysis
│
├── WorkingReportAgent
│   ├── Professional report generation
│
├── PadWasteGuardWorking
│   ├── Orchestrates full pipeline
│   ├── Single & batch image processing
│
└── Demo Execution
    ├── Sample image analysis
    ├── Report & summary output
