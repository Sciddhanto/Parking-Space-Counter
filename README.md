### Parking Space Counter 

#### Overview
The "Parking Space Counter" is a Python-based application designed to detect and count occupied and vacant parking spaces using computer vision. It processes video feeds to monitor parking availability in real time, making it suitable for parking management and smart city solutions.

#### Features
- Real-time detection of occupied and vacant parking spaces.
- Dynamic color-coding (green for vacant, red for occupied) of parking slots.
- Customizable parking space regions using a GUI-based tool.

#### Installation

### Prerequisites
- Python 3.x
- OpenCV
- NumPy

**Installation Steps**:
1. Install the required libraries:
   - Using pip:
     ```
     pip install opencv-python numpy
     ```
   - Using Conda:
     ```
     conda install -c conda-forge opencv numpy
     ```

2. **Clone the Repository**:
   ```
   git clone https://github.com/Sciddhanto/Parking-Space-Counter.git
   cd Parking-Space-Counter
   ```

3. **Run the Main Script**:
   ```
   python main.py
   ```

#### Usage Instructions
1. **Define Parking Spaces**:
   - Run `ParkingSpacePicker.py` to manually select and save parking space regions.
   - Use the Tkinter-based interface to mark corners of parking slots and save the coordinates.

2. **Monitor Parking**:
   - Run `main.py` to start real-time monitoring of parking spaces.
   - The script will display the parking status with color-coded rectangles and update the count of available spaces.

3. **Exit and Save**:
   - Close the video window or press any key to stop the program.

#### File Descriptions
- `main.py`: The main script for processing video feeds and detecting parking occupancy.
- `ParkingSpacePicker.py`: A script for setting up parking space regions via a graphical interface.
- `CarParkPos`: A configuration file containing saved parking space coordinates.

#### Future Enhancements
- Incorporate advanced object detection models like YOLO.
- Implement cloud-based storage for parking data.
- Develop a mobile application for users to view live parking availability.
- Add support for edge computing to optimize performance.

#### Contributing
To contribute to this project, fork the repository and submit a pull request with your updates or improvements.

#### Acknowledgements
The tool is built using OpenCV and other Python libraries for efficient real-time image processing.
