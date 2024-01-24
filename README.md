# User evaluation of the relationship between NAS and explainable AI.

## Abstract
　This experiment is designed to verify the performance and explainability of the image classification model created by Neural architecture search(NAS).
The experimental procedure is described below.

## Experiment
### Content
 This experiment is a model of a 10-classification task using the cifar-10 dataset.

### Step
1. Double-click the file **"GUI_multi.exe"** in the folder.

2. After successful startup, a command prompt or terminal (black screen) and a white window will open.

3. Check the leftmost number at the bottom and press the "Start" button.

4. The image is displayed on the screen. The red-highlighted areas in the rightmost image are the areas that are strongly affected by the model's decisions. Use the slider to indicate how well the red highlighted area matches the area that you have determined to be the label (e.g., airplane).
>The more closely matched the value is, the closer it is to 10, and the less closely matched the value is, the closer it is to 0.

5. Once you have decided on the evaluation, press the "Next" button.

6. You will do this until you have completed 100 sheets.

7. Perform these operations 1-6, changing the numbers in step 3 from (1) to (7).

 Finally, several log files will be generated in a folder named "log_list".
ex) 1702479262.9748728_test.log 

Please send the generated log file to the following e-mail address

## Mail
f23c001b@mail.cc.niigata-u.ac.jp
