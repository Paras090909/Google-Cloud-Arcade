📌 LAB LINK: 
https://www.cloudskillsboost.google/games/6059/labs/38581

This guide will help you complete the Measuring and Improving Speech Accuracy with straightforward steps. Just follow the commands provided to successfully finish the lab and showcase your skills.
Follow these simple steps to complete the Challenge Lab successfully:
----------------------------------------------------------------------
✅ STEP 1: Configure Zone Variable
Set the required environment variables by running the following commands in Cloud Shell:
export ZONE=

👉 Note: Make sure to specify the correct zone for the lab.
-----------------------------------------------------------------

✅ STEP 2: Execute the Script
Copy and run these commands in Cloud Shell:


curl -LO raw.githubusercontent.com/QUICK-GCP-LAB/2-Minutes-Labs-Solutions/main/Measuring%20and%20Improving%20Speech%20Accuracy/gsp758.sh
sudo chmod +x gsp758.sh
./gsp758.sh
👉 Note: Make sure to specify the correct zone for the lab.

--------------------------------------------------------------------

✅ STEP 3: Copy Files to Notebook Terminal
Navigate to Workbench and run the following commands in the Notebook Terminal:


gsutil cp gs://spls/gsp758/notebook/measuring-accuracy.ipynb .
gsutil cp gs://spls/gsp758/notebook/speech_adaptation.ipynb .
gsutil cp gs://spls/gsp758/notebook/simple_wer_v2.py .

--------------------------------------------------------------------


🎉 Congratulations!
You've successfully completed the lab! Your skills and hard work have paid off. Well done! 👏
✅ Remember to close the incognito tab after completing the lab.


