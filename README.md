# LeapMotionController
## Install
- Install MyStudio  https://github.com/elephantrobotics/MyStudio/releases
- Download Leapmotion  
    ![Download Leapmotion](https://user-images.githubusercontent.com/48149929/122377161-69626700-cf97-11eb-87b9-5d885db2c1d6.png)
- install this two file
    ![install this two file](./res/step1.png)
- Burn AtomMain（MyStudio->Basic->AtomMain）into ATOM   
    ![Burn AtomMain into ATOM](https://user-images.githubusercontent.com/48149929/122373873-6ca82380-cf94-11eb-8c15-db411fbf3a16.png)  
  Burn Transponder（MyStudio->Tools->Transponder）into BASIC  
    ![Burn Transponder into BASIC](https://user-images.githubusercontent.com/48149929/122374042-9a8d6800-cf94-11eb-86eb-6d9b2eb79c67.png) 
## How to use LeapmotionController to control MyCobot  
- check the usb port
    ![check the usb port](./res/step2.png)
- enter the port
    ![enter the port](./res/step3.png)
- After LeapmotionController successfully starts, Mycobot will adjusts to initial position automatically 
- Use gestures to control MyCobot to move

### Tips：
1. If you start LeapMotionController and enter port number, it stops on the following page and you cannot control MyCobot through LeapMotion  
    ![image](https://user-images.githubusercontent.com/48149929/122374352-e2ac8a80-cf94-11eb-8691-6dda8c009777.png)  
   Check that the driver has been installed successfully:  
    ![image](https://user-images.githubusercontent.com/48149929/122374387-ec35f280-cf94-11eb-8c55-735d46e96267.png)  
   If the driver has been successfully installed but the version is too low, it is recommended to change to the driver provided by us
2. When controlling MyCobot with Leapmotion, Mycobot will return to initial position when the hand is out of range of Leapmotion’s detection
3. MyCobot moves in response to gesture and cannot hover in one position
