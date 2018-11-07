# google-assistant-sdk

## Setup
### Setup google assistant
please follow the tutorial ```Embed the Google Assistant``` on this link to setup, you **dont** need to do ```Extend the Google Assistant```

when it require you to install python in virtual environment, **DONT**, otherwise you will need to install **ROS** relate package in it as well to make it work.

https://developers.google.com/assistant/sdk/guides/library/python/embed/setup

### Setup ROS with it
     git clone https://github.com/googlesamples/assistant-sdk-python

#### Find the command handler
The ```hotword.py``` file in the sample code uses the SDK to send requests and receive responses from the Google Assistant.

    cd assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/library

refer to ```ROS Writing a Simple Publisher and Subscriber``` Tutorial to setup ROS in ```hotword.py``` file to enable ROS with google assistant 

http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28python%29

Run your modified source code directly to see the output.

    python hotword.py --device-model-id <your-model-id>
    
### Google Assistant python library
https://developers.google.com/assistant/sdk/reference/library/python/

### Check the example code provided in this git repository on how to use ROS with google assistant
https://github.com/cricel/google-assistant-sdk/blob/d8de5cc154a68eef19aa0cd5bcc1cda290464f68/hotword.py#L68
