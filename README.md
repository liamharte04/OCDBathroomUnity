**README: OCD Bathroom Exposure Therapy Game**

---

### Project Overview
This project is a Virtual Reality (VR) application designed as an exposure therapy tool for individuals with Obsessive-Compulsive Disorder (OCD). Specifically, the VR simulation focuses on contamination-related OCD triggers commonly associated with bathroom environments. The game was built in Unity and is intended to support clinical trials as part of an OCD research study led by a Senior Lecturer in Psychology at Queen’s University Belfast. The VR experience aims to simulate real-world scenarios to help users confront their contamination fears in a controlled, safe setting. 

### Purpose and Objectives
The VR experience aims to:
- Facilitate controlled exposure to contamination-related triggers in a bathroom setting.
- Provide customizable exposure options to allow gradual exposure therapy tailored to individual comfort levels.
- Support clinical trials by offering a reproducible, immersive exposure environment to help participants reduce distress associated with contamination fears.

### Key Features
1. **Realistic Bathroom Environment**  
   A detailed 3D bathroom with various interactive elements that mimic real-life triggers for contamination-related OCD. Objects such as the sink, toilet, taps, and soap dispenser are modeled to closely resemble real bathroom features.

2. **Progressive Exposure Levels**  
   Multiple levels of exposure are designed to gradually introduce contamination triggers. Users can begin with low-stress tasks (e.g., turning on the sink) and progress to more challenging interactions (e.g., touching the toilet or handling soap without washing).

3. **User Interaction and Real-Time Feedback**  
   Interactive elements allow users to engage with objects in the bathroom. Feedback mechanisms (e.g., visual prompts) help users understand and reflect on their responses to contamination cues.

4. **Therapist/Admin Control Panel**  
   A control panel accessible to therapists or study administrators allows customization of exposure settings. For instance, the panel can control which objects are interactable and adjust the level of contamination simulation for each object.

5. **Data Collection for Clinical Trials**  
   Data on user interactions, exposure duration, and physiological responses (if integrated with biometric sensors) are collected. This data assists researchers in assessing the effectiveness of VR exposure therapy.

### Technical Specifications
- **Platform**: Unity 2021.3 or later
- **Target Devices**: Meta Quest or similar standalone VR headsets
- **Programming Language**: C#
- **Rendering Pipeline**: Unity Universal Render Pipeline (URP) for optimized VR performance
- **External Libraries/SDKs**: Meta’s All-In-One SDK for VR interaction, Oculus Integration package for Unity

### Setup Instructions
1. **Environment Setup**  
   - Install [Unity Hub](https://unity3d.com/get-unity/download) and add Unity 2021.3 or later.
   - Open the Unity project folder in Unity Hub and select the project.

2. **Configure VR Device**  
   - Ensure your VR headset (e.g., Meta Quest) is connected and set up in Developer Mode.
   - Set up VR build settings: go to *File > Build Settings* and select *Android* as the platform (if using a standalone VR headset like Meta Quest).
   - Enable VR support in *Project Settings > XR Plug-in Management*.

3. **Run the Simulation**  
   - Open the scene titled `OCD_Bathroom_Simulation`.
   - Press the *Play* button in Unity’s editor to test the game or build the project for deployment on a VR headset.

### Usage Guide
1. **For Therapists and Researchers**  
   - Access the therapist control panel at the start of each session to customize exposure scenarios.
   - Use data logs to monitor user progress and evaluate therapy outcomes.

2. **For Participants**  
   - Participants wear the VR headset and are guided through various exposure tasks by the therapist.
   - Prompts and cues are provided to encourage participants to engage with each object in the bathroom.

### Data Collection and Privacy
- Data collected from each session is stored locally on the device and can be exported for analysis.
- Personal identifiers are anonymized to protect participant privacy in line with Queen’s University Belfast’s ethical guidelines.

### Future Development
Potential future updates include:
- Adding additional environments or scenarios to broaden the range of exposure triggers.
- Integrating biometric feedback for real-time assessment of stress and anxiety.
- Enhancing interaction realism with haptic feedback.

---

### Contact Information
This application was developed by Liam Harte, a Virtual Reality Researcher, as part of a VR research project at Queen’s University Belfast. For inquiries or further information, please contact the Psychology Department or reach out via email: lharte08@qub.ac.uk
