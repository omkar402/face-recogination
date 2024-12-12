# Face Recognition Attendance System

## Steps to Set Up and Run the Project

1. **Download or Clone the Repository**
   - Clone this repository to your local machine or download it as a ZIP file and extract it.

2. **Install Dependencies**
   - Open a command prompt and navigate to the project folder.
   - Run the following command to install the required packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Create a `TrainingImage` Folder**
   - In the project directory, create a folder named `TrainingImage`.

4. **Update File Paths**
   - Open `attendance.py` and `automaticAttendance.py`.
   - Update all file paths in the scripts to match the paths on your system.

5. **Run the Project**
   - Execute the `attendance.py` file to start the application.

## Project Flow and Explanation

### 1. Registering a New Student
- After launching the application, click on the **Register New Student** button.
- A small window will pop up where you can enter the student's ID and name.
- Click on the **Take Image** button.
  - This will open a camera window.
  - The system will detect your face and capture up to 50 images (you can modify the code to change this number).
  - The images will be stored in the `TrainingImage` folder.
  - **Tip:** The more images you provide, the better the system's face recognition performance will be.

### 2. Training the Model
- Click on the **Train Image** button.
  - This will train the model and convert the captured images into numeric format, which the computer can understand.
  - The training process duration depends on your system's performance.

### 3. Taking Attendance
- Click on the **Automatic Attendance** button.
  - Enter the subject name.
  - The system will use the trained model to recognize faces and mark attendance automatically.
  - Attendance data will be saved as a `.csv` file, with separate files created for each subject.

### 4. Viewing Attendance
- Click on the **View Attendance** button.
  - Attendance records will be displayed in a tabular format for easy review.

## Notes
- Ensure that the camera on your system is functional and properly configured.
- Update paths and configuration details to align with your environment.

Enjoy using the Face Recognition Attendance System!
