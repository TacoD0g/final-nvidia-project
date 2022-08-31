# final-nvidia-project

This program reads letters and determines what letter it is looking at. This would be useful when further improved on to those who need to take written words and quickly copy it onto a computer.

![A picture of me taking pictures for the dataset](https://i.imgur.com/3JgSRws.png)

## The Algorithm

The algorithm first reads the camera and connects it to the jetson nano. It creates the task name and categories 'a' through 'z'. Next it imports some of the widgets needed to collect any of the images used as the dataset. Then it defines the neural network model and sets up the live execution widget. Lastly, it defines the trainer and the widgets needed to control, followed by the code that activates all widgets and lets you interact with the program. 

## Running this project

To begin, you go through PuTTY or Windows PowerShell and open up your JupyterLab. You create a new Kernel and put in all of the given code. Next, you take pictures letters and put them in the correct categories. I used 11 different alphabets from a total of 8 different people, then took 5 pictures of each letter of each alphabet. Lastly, you set the epoches to about 20 or 30 and then try pointing the camera at some of the letters. If enough pictures were taken at various angles, it should provide the right letter 90% of the time.

Video Demonstration: 
https://youtu.be/Bpc4ptw2bpw
