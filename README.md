# Age Classification using Deep Learning
 
This project was conducted using a dataset provided in by the University. 
The dataset consisted of 19,000 images approximately. The Dataset split into three categories that were Old, Middle and Young. The number of files were unevenly distributed among the three as you can see from below.

![image](https://github.com/user-attachments/assets/3ac226ca-278b-4601-96ff-48dac5116e0e)


There are two files here:
1 Image Data Generator- Here the Augmentation techniques applied were using Image Data Generator.
2 Pillow Library- Here the Augmentation technique applied were using Pillow Libraries.

The images were resized to (64,64) as this was run originally on Google Colab. The algorithm used here was Basic CNN.
The first file mentioned here were using Image Data Generator gave us the acccuracy 82% and 80% in both training and testing respectively which ran for 100 Epochs.
The second file mentioned here were using the Pillow Library, although this was ran for only 20 Epochs, the result was overfitting where the training accuracy was around 94% and testing accuracy was 72%.
So the model or in precisely the file we considered as successful was the one using Image Data Generator.

The model was finally deployed using Anvil Web App. The link is 'https://age-classification-ai.anvil.app/'

The link won't work without the program being run in live.

Below is the process of running this.

![process of anvil](https://github.com/user-attachments/assets/eda26948-0299-4b60-b423-a04c934ad921)


Below is the trial run for this app.

![anvil prediction](https://github.com/user-attachments/assets/e17ce89a-6598-4f4f-9e16-07983de40656)
