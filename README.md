# Rasptank Robot

**Python-powered Raspberry Pi tank** with:
- 4-DOF robotic arm (ADAfruit ServoKit)  
- OpenCV target tracking via Pi Camera  
- Flask-based control web interface  

## Project Roadmap
1. **Assembly**: chasssis, tracks, arm, Pi & camera setup  
2. **Motor Control** (`src/motors.py`)  
3. **Arm Control** (`src/arm.py`)  
4. **Vision** (`src/vision.py`)  
5. **Web UI** (`src/webapp.py`)  
6. **Integration & Testing**

## Getting Started
```bash
git clone git@github.com:lee1981b/RaspTank-Robot.git
cd RaspTank-Robot
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
