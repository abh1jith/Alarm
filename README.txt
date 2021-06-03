# Alarm using Python
This is a GUI and API Based Alarm. While running, it will notify you with an alarm(Audio File is also uploaded) and will text you an SMS on the number specified.
NOTE: For security reasons my Developer API Key is not provided. You can create one at www.fast2sms.com and head over to Dev API for the key after registering.

Before running the code in Python3, do follow the instructions mentioned as follows:

=> Install latest version of Python.
=> Install the following mdules through command prompt(Mandatory for the code to run)
  You can install them by typing the code in the paranthesis in cmmand prompt.
requests  (pip install requests)
tkinker   (pip install tk)
daytime   (pip install daytima)
pygame    (pip insall pygame)

=> Place the Audio file named "MyAudio.wav" in the same directory as the code.
{WARNING: DO NOT CHANGE THE NAME OF THE AUDIO FILE SINCE THE CODE CANNOT DETECT THE FILE ON ITS OWN.}
=> Create an account at www.fast2sms.com and verify your account.
=> Copy the Dev API key and place that in the code mentioned. (Line 10 to be exact)
=> Change the message as required in the message attribute inside send_message() function and 'payload' attribute. (Line 6 to be exact)
=>Run the code and do not close until you get the output. Since, it cannot run in the background.



Thanks and Regards
Abhijith Dameruppala
