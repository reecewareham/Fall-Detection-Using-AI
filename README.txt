Instructions to run all the code from the project:

If running on local machine:

1. Make sure Python is installed. Most compatible python version is Python 3.10.11.
2. Make sure Juptyer Notebook is installed. This can be done using PIP.
3. Make sure all required libraries are installed for each code file. All files have the included PIP commands to install the libraries.
4. Once previous steps are complete, open code in preferred IDE (Most simple IDE to get working is Visual Studio Code) or open code in Jupyter Notebook.
5. Select correct Python environment. Most ideal and tested version is Python 3.10.11.
6. Run each code segment in order starting from the top. This ensures there will be no errors.

If running in Google Colab:

1. Upload each file to your Google Drive.
2. Open the desired file from your Google Drive in Google Colab.
3. Run each code segment in order starting from the top. This ensures there will be no errors.


What do each files do?

Final_Pose_Detection_Tool - Used to create a skeleton model on video files. Also extracts the landmark coordinates of the skeleton and saves it as a CSV file.
Updated_Fall_Detection_SVM - Used to create and train a support vector machine. Can also be used to test the trained model by using the testing portion of the dataset. Gives valuable metrics on the performance of the model.
Merging Annotation and Data - Used to merge the CVAT annotations and the extracted landmark coordinates CSV files together into 1 file. Combining creates 1 sample of the dataset.
Camera_GUI - Testing GUI code that can display a video stream or video file. Makes predictions on the video in real time whilst displaying the model outcome and the landmark coordinates of the pose detector.
Updated_SVM_Model - The SVM model saved as a JobLib file. Can be loaded directly, skipping the model training process.
Camera_Testing_Code - Used to test the model on a realtime live video stream. Very basic but displays video stream with either no fall or fall prediction. Includes a notification system that can send notifications when a fall is detected. Setup DroidCam app to use live video stream.
MP4_Testing_Code - Similar to last code, but instead of using a live video stream, it uses MP4 files instead.
Camera Tracker - Camera testing code that tracks a person and displays a skeleton model on top. Doesn't make predictions but is used to demonstrate the pose detection in action.
Combined Final Dataset Folder - Contains the final dataset made up of real life and GTA V CSV files. To find the full dataset with included videos, check the Google Drive Training / Testing Dataset folder (Link found on Blackboard).
Final Project Documents - An extra copy of all the final documents for this project.



!!WARNING!!
SOME OF THE CODE WILL NOT WORK PROPERLY IN GOOGLE COLAB. THE CODE THAT DOESN'T WORK IS ANY CODE THAT IS USED TO CREATE A LIVE VIDEO STREAM. 
THIS MUST BE DONE IN LOCAL MODE DUE TO COLAB LACKING A WAY OF DISPLAYING A GRAPHICAL INTERFACE.


If there are any more files that you wish to view such as previous work, please check the Google Drive link found on Blackboard or in the Final Project Documents folder to see all files associated with the project, both old and new.

Thank you for reading,

-The Fall Guys (Group 5)

