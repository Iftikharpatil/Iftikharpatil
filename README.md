import pyautogui
import time
pwd=6365;
time.sleep(3)

for i in range(1000,9999):
    pyautogui.typewrite(str(i))
    pyautogui.press("enter");
    if pwd==i:
            print(i);
// these is code to crack password using hackypi usb for only 4 digit password 
