# Demographic Characterstics and Emotion Prediction in Video Meetings


 * Project strcture
	- Demographic_Char_Emo_Prediction.ipynb contains prediction script which loads model that we have trained in Training_Script.ipynb
	- Create frame and faces folders (which will be empty initially, will be used to stores data while running project)
	- models - AGR and Emo models
 * Requirements
	- cv2, keras, PIL, numpy, tesnsorflow, matplotlib, mtcnn, sklearn, pandas, seaborn, math
 * Use sample video with multiperson meeting for testing



### Instruction to run project 

1. To train run Training_Script.ipynb
2. To test results run Demographic_Char_Emo_Prediction.ipynb 

### Output

Age, gender, race and emotion mentioned in the top box for each participant in the online video meeting.

<img src="Screenshot 2023-06-02 at 3.01.19 PM.png" width="700"/>
