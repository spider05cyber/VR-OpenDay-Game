# CyberQuest: Progression Zones  
**An Immersive VR Learning Experience**

## **Purpose**  
CyberQuest: Progression Zones is an immersive virtual reality application designed to teach fundamental computing logic and cybersecurity concepts in an engaging, gamified environment. By combining interactive problem-solving with a futuristic cyberpunk theme, this project aims to bridge the gap between theoretical knowledge and practical application.  

The world consists of four distinct levels: the **Lobby**, **Office**, **Bedroom**, and **Server Room**. Each level presents unique challenges:  
1. **Office** – Solve pseudocode logic problems in a dilapidated, cyberpunk-styled office.  
2. **Bedroom** – Engage in an escape-room-style activity to identify security flaws related to social engineering.  
3. **Server Room** – Analyze and respond to simulated cybersecurity threats in a high-pressure environment.  
4. **Lobby** – The starting area that introduces players to the tutorial and objectives for each level.  

The experience leverages the power of virtual reality to make learning engaging and memorable through realistic interactions, spatial audio, and captivating visuals.

---

## **Technical Implementation**  

CyberQuest was developed using **Unity’s XR Interaction Toolkit**, chosen for its flexibility and compatibility across VR and PC platforms. The VR version was tested on the Meta Quest 3 headset, while the PC version supports traditional keyboard and mouse input.  

- **Navigation & Interaction**:  
  - VR: Players use joysticks for movement, with a tunneling vignette to reduce motion sickness, and hand controllers to project “raycasts” for interacting with objects.  
  - PC: Movement is enabled with the WASD keys, and a central reticle is used for object interaction via mouse clicks and mouse movement.  
  - Raycast technology ensures intuitive interaction, with visual feedback (e.g., changing ray colors) and haptic cues enhancing user affordances.  

- **Design Consistency**:  
  Textures were sourced from a central pack for visual cohesion, while some custom assets (e.g., interactive safes, quiz boards) were created using ProBuilder. Spatial audio, realistic lighting, and a skybox consistent with the cyberpunk theme further enhance immersion.

- **Gamified Elements**:  
  - Levels are structured to provide immediate feedback (e.g., correct/incorrect answers) and a sense of accomplishment upon progression.  
  - Exploration is encouraged with interactive objects that provide both auditory and visual responses.  

---

## **How to Use CyberQuest**  

### **Running the Application**  
- **VR Version**: Install the “MetaBuild.apk” file on a Meta Quest 3 headset and launch the application.  
- **PC Version**: Run the executable file from a Windows PC.  

### **Controls**  
- **VR**:  
  - Movement: Use the joystick on the VR controller.  
  - Interaction: Point the controller’s raycast at objects and press the trigger to select.  
- **PC**:  
  - Movement: WASD keys.  
  - Interaction: Align the red reticle with objects using the mouse and left-click the mouse to interact with objects.  

### **Gameplay Flow**  
1. Spawn in the **Lobby**: Read instructions about each level on the panels and select a floor using the elevator.  
2. Complete tasks in the chosen level:  
   - **Office**: Solve multiple-choice pseudocode problems.  
   - **Bedroom**: Identify security flaws by clicking on objects in the room.  
   - **Server Room**: Analyze server defense problems and select the correct strategy.  
3. Return to the elevator to explore other floors.  

---

## **User Experience**  

CyberQuest creates a highly immersive and interactive learning environment through:  
- **Visual and Audio Design**: Detailed textures, a cyberpunk-themed skybox, and spatial audio effects create a sense of presence.  
- **Interactivity**: Players actively engage with their environment by solving puzzles, exploring, and interacting with objects.  
- **Accessibility**: Smooth, frame-rate-independent controls reduce motion sickness and ensure ease of navigation.  

---

## **Conclusion**  

CyberQuest: Progression Zones combines the power of VR with gamified learning to make computing and cybersecurity concepts exciting and accessible. Its immersive design, interactive gameplay, and real-world relevance make it an ideal tool for both education and entertainment.

--- 