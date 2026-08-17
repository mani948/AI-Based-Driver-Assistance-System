# AI-Based Driver Assistance System Using Computer Vision and Deep Learning for Real-Time Road Safety

## Team Members

| **Name**         | **ID Number** |
| ---------------- | ------------- |
| G. Manikanta     | 2420030366    |
|I.Vishnu Vardhan  | 2420030513    |


## Supervisor

**Supervisor Name:** V.Ramya

---

## Abstract

The abstract of the project is provided as a separate PDF document.

[**View Abstract**](docs/)

---

## Project Description

The **AI-Based Driver Assistance System Using Computer Vision and Deep Learning for Real-Time Road Safety** is designed to improve road safety by assisting drivers in identifying potential hazards and making safer driving decisions.

The proposed system continuously analyzes camera or video input using **Computer Vision and Deep Learning** techniques to detect important road elements such as vehicles, pedestrians, obstacles, traffic signs, and road lanes.

The system further analyzes the detected objects, lane position, and approximate distance to identify potentially dangerous situations such as **lane departure, unsafe proximity, and possible collision risks**.

When a hazardous situation is detected, the system generates appropriate **audio or visual alerts** to warn the driver in real time. The overall system follows a processing pipeline consisting of camera/video input, object detection, lane detection, risk analysis, danger identification, and driver alert generation.

The proposed system focuses on reducing accidents caused by human error and improving driver awareness through timely safety warnings. It can be implemented and evaluated using recorded road videos or a simulated environment, allowing its performance to be tested under different road and traffic conditions.

The system will be evaluated based on factors such as **object detection accuracy, lane detection accuracy, hazard identification accuracy, and response time**. Overall, the project aims to provide a practical AI-based driver assistance prototype that contributes to safer, more intelligent, and reliable driving.

---

## Objectives

* Develop an AI-based system for real-time driver assistance.
* Detect vehicles, pedestrians, obstacles, and traffic signs from camera/video input.
* Detect and monitor road lanes using Computer Vision techniques.
* Identify lane departure and unsafe driving conditions.
* Estimate approximate distance between the vehicle and detected objects.
* Identify potential collision and road-safety risks.
* Generate real-time audio or visual alerts for detected hazards.
* Apply Deep Learning and Computer Vision techniques to improve road-scene understanding.
* Reduce the risk of accidents caused by human error.
* Evaluate the system based on detection accuracy and response time.

---

## Key Features

* **Real-time video processing**
* **Vehicle detection**
* **Pedestrian detection**
* **Obstacle detection**
* **Traffic sign detection**
* **Lane detection**
* **Lane departure warning**
* **Approximate distance estimation**
* **Collision-risk detection**
* **Driver alert generation**
* **Audio and visual warnings**
* **Deep Learning-based object recognition**
* **Computer Vision-based road analysis**
* **Performance evaluation dashboard**

---

## System Workflow

```text
Camera / Video Input
        ↓
Frame Extraction
        ↓
Image Preprocessing
        ↓
Object Detection
        ↓
Lane Detection
        ↓
Distance / Position Analysis
        ↓
Risk Analysis
        ↓
Hazard Identification
        ↓
Driver Alert Generation
        ↓
Audio / Visual Warning
```

---

## Technologies Used

* **Programming Language:** Python
* **Computer Vision:** OpenCV
* **Deep Learning:** TensorFlow / Keras
* **Object Detection:** YOLO or other suitable deep learning model
* **Data Processing:** NumPy, Pandas
* **Visualization:** Matplotlib
* **Interface:** Streamlit
* **Development Environment:** Jupyter Notebook / VS Code
* **Version Control:** Git
* **Repository:** GitHub

> The exact libraries and models may be updated during implementation based on project requirements.

---

## Machine Learning / Deep Learning Components

### 1. Object Detection

The system detects important road objects such as:

* Cars
* Buses
* Trucks
* Motorcycles
* Pedestrians
* Traffic signs
* Other obstacles

A Deep Learning-based object detection model can be used to identify objects and determine their positions within each video frame.

### 2. Lane Detection

Computer Vision techniques are used to identify road lane markings and estimate the position of the vehicle relative to the lane.

The system can generate a warning when the vehicle moves outside the expected lane boundaries.

### 3. Distance Estimation

The system analyzes the detected objects and their position in the video frame to estimate approximate distance or proximity.

This information can be used to identify situations where another vehicle or obstacle is dangerously close.

### 4. Risk Analysis

The detected information is combined to identify potentially dangerous situations, including:

* Unsafe following distance
* Possible collision
* Lane departure
* Pedestrian proximity
* Obstacles in the driving path

### 5. Driver Alert

When a potential hazard is identified, the system generates an appropriate warning through:

* Audio alerts
* Visual warnings
* On-screen notifications

---

## Project Structure

```text
AI-Based-Driver-Assistance-System/
│
├── README.md
│
├── docs/
│   └── ProjectAbstract.pdf
│
├── src/
│   ├── app.py
│   ├── object_detection.py
│   ├── lane_detection.py
│   ├── risk_analysis.py
│   ├── alert_system.py
│   ├── preprocessing.py
│   └── ...
│
├── models/
│   └── trained_model/
│
├── dataset/
│   ├── images/
│   ├── labels/
│   └── videos/
│
├── results/
│   └── ...
│
├── requirements.txt
└── ...
```

> The project structure may be updated as development progresses.

---

## Setup and Execution Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd AI-Based-Driver-Assistance-System
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

If the project uses Streamlit:

```bash
streamlit run src/app.py
```

### 7. Open the Application

After running the command, Streamlit will provide a local URL, typically:

```text
http://localhost:8501
```

Open the URL in a web browser to access the application.

---

## Input and Output

### Input

The system can accept:

* Live camera input
* Recorded road videos
* Road-scene images
* Simulated driving environments

### Processing

The input is processed using:

1. Image/frame preprocessing
2. Object detection
3. Lane detection
4. Object position analysis
5. Distance estimation
6. Risk analysis
7. Hazard classification

### Output

The system provides:

* Detected objects
* Detected lane boundaries
* Vehicle/lane position
* Hazard identification
* Collision-risk warning
* Lane departure warning
* Audio alerts
* Visual alerts

---

## Example Safety Scenarios

| **Scenario**                        | **System Response**         |
| ----------------------------------- | --------------------------- |
| Vehicle detected at unsafe distance | Collision/proximity warning |
| Vehicle leaves lane                 | Lane departure warning      |
| Pedestrian detected ahead           | Pedestrian warning          |
| Obstacle detected in driving path   | Obstacle warning            |
| Traffic sign detected               | Traffic sign identification |
| Multiple hazards detected           | Appropriate safety alert    |

---

## Performance Evaluation

The proposed system can be evaluated using the following metrics:

* **Object Detection Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Lane Detection Accuracy**
* **Hazard Detection Accuracy**
* **False Positive Rate**
* **Response Time**
* **Frames Per Second (FPS)**

These metrics help determine how effectively the system performs under different road, lighting, traffic, and environmental conditions.

---

## Current Phase Status

### Phase 1 – Project Planning

**Status: Completed ✅**

* Project idea finalized
* Problem statement identified
* Project objectives defined
* Technology stack identified
* Team responsibilities discussed

### Phase 2 – System Design

**Status: In Progress 🔄**

* System architecture being designed
* Object detection workflow planned
* Lane detection workflow planned
* Risk analysis workflow planned
* Driver alert mechanism planned
* User interface design in progress

### Phase 3 – Implementation

**Status: Not Started ⏳**

* Dataset preparation
* Image/video preprocessing
* Object detection implementation
* Lane detection implementation
* Distance estimation
* Risk analysis
* Alert generation
* Application interface development

### Phase 4 – Testing and Evaluation

**Status: Not Started ⏳**

* Model testing
* Detection accuracy evaluation
* Lane detection testing
* Hazard detection testing
* Response-time evaluation
* Real-world/recorded-video testing

### Phase 5 – Deployment

**Status: Not Started ⏳**

* Application optimization
* Final integration
* Deployment
* Documentation
* Final project demonstration

> Update the phase statuses according to the actual progress of the team.

---

## Advantages

* Improves driver awareness.
* Provides timely warnings about potential hazards.
* Helps identify lane departure.
* Detects vehicles, pedestrians, and obstacles automatically.
* Reduces dependence on continuous manual observation.
* Demonstrates practical applications of AI and Computer Vision.
* Can be tested using recorded road videos without requiring a physical vehicle.
* Provides a foundation for future intelligent transportation systems.

---

## Applications

The proposed system can be used or extended for:

* Advanced Driver Assistance Systems (ADAS)
* Smart vehicles
* Intelligent transportation systems
* Driver safety monitoring
* Autonomous driving research
* Traffic safety research
* Automotive AI applications
* Driving simulation systems

---

## Future Enhancements

* Integrate GPS and real-time map information.
* Improve object detection using advanced YOLO models.
* Add real-time traffic sign recognition.
* Improve distance estimation using depth estimation.
* Add vehicle speed estimation.
* Implement driver drowsiness detection.
* Add night-time and adverse-weather detection.
* Integrate with IoT-enabled vehicles.
* Develop a mobile or edge-device version.
* Deploy the system on Raspberry Pi, NVIDIA Jetson, or other edge-AI devices.
* Add emergency notification capabilities.
* Integrate with real-world vehicle safety systems.
* Improve performance using larger and more diverse road datasets.

---

## Limitations

The prototype may have limitations under conditions such as:

* Poor lighting
* Heavy rain or fog
* Occluded objects
* Low-quality cameras
* Poorly visible lane markings
* High traffic density
* Unusual road conditions

The system is intended as an **academic/research prototype** and should not be treated as a replacement for certified automotive safety systems.

---

## License

This project is developed for **academic and educational purposes**.

---

## Team

**G. Manikanta** — 2420030366
**Y. Gowtham** — 2420030522
**M. Mahidhar** — 2420030756
**M. Arjun Reddy** — 2420030559

**Supervisor:** RajKumar Patil
