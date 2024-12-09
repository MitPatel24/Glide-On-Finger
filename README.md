# Glide On Finger: A Virtual Mouse 🖱️🤚

  
Control your computer with a movement of fingers– effortless, touchless navigation! ✋💻

---

## 📜 **Project Description** 
"Glide On Finger: A Virtual Mouse" is an innovative application that transforms your hand into a virtual mouse. Using a webcam and hand-tracking technology, it allows users to control their computer cursor through simple finger movements. It also features click actions triggered by finger gestures, enabling a seamless touchless experience. 🤳🖱️

---

## 📂 **Features**  
- Hand-tracking using Mediapipe.  
- Cursor movement via finger gestures.  
- Click detection through finger proximity.  
- Adjustable frame reduction for precise tracking.  
- Real-time performance with FPS display. ⏱️

---

## 🚀 **Getting Started**  
### **Prerequisites**   
* Ensure the following libraries are installed with the specified versions: 

    ```bash
        opencv-python==4.10.0.84  
        numpy==1.26.4  
        mediapipe==0.10.9  
        pyautogui  

### **Installation** 
1. Clone the repository:

    ```bash
    git clone git@github.com:MitPatel24/Glide-On-Finger.git
    cd <project-directory>

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt

### 📋 **Usage**
1. Run the script:
    ```bash
    python main.py

2. Ensure your webcam is functional and positioned correctly.

3. Use your index finger to move the cursor and perform clicks with finger gestures.

### 🎨  **Customization**
* Frame Reduction (frameR):This value controls the size of the frame within which the hand is tracked. A smaller value will track your hand more precisely but reduce the effective area for gestures.
    ```bash
    frameR = 100  # Default value
* Smoothening (smoothening):This smoothens the cursor movement. A higher value makes the cursor movement slower and more fluid, while a lower value results in faster but less smooth movement.
    ```bash
    smoothening = 7  # Default value

## **Contributors**
- Mitkumar Patel -  [MitPatel24](https://github.com/MitPatel24)
