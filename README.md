# DeepGuard: A Custom Built Novel Detection Framework for Combating Deepfakes, Voice Spoofing and Speech Deciphering.

## We built out a novel agent framework to detect deepfakes, artificial voice generation, and falsified speech by creating a multimodal approach which utilizes Video, Audio and Text extraction combined with the latest AI frameworks. 

In the age of social media, deepfakes have become widely prevalent and more realistic. Our custom application, DeepGuard, built off a Novel Detection Framework, allows users to input a deepfake video and then takes a multimodal approach to accurately detect false video, speech, or audio within the video and inform users. Unlike many current day detection algorithms, DeepGuard is the first of its kind to be able to parse through the audio, video, and speech of a video rather than focusing on one of the three, making it more accurate and adaptable. Some cool key features include:

* Video Input: Users can choose any deepfake as long as it comes in MP4 format
* Name and Context Utilization: Users can choose to incorporate name and context to make speech deciphering more accurate.
* Audio and Video Extraction: Audio and Video feature extraction to make detection more accurate
* Speech to Text Extraction: Converts the deepfake subject's speech to text 
* Speech Deciphering: Using ChatGPT, takes in name, context, and text extraction to determine if the subject of the video would say the text in real life.
* Voice Spoofing: ML algorithm trained on custom voice datasets to identify real versus AI-generated/fake audio.
* Visual Deepfake Detection: Runs video through Arya API to analyze deepfakes visually.
* Test Customization: Allows users to run specific or all tests, making it applicable to any of the above domains.
* UI Feedback: Outputs confidence scores for each test as well as custom explanations via ChatGPT.
  
![agent-flow-chart](Flowchart.png)

Built by Nyan Prakash, Shaunak Sinha, & Brennan Pan.
