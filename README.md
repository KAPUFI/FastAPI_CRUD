# CONFIGURE BURP-SUITE AND FIREFOX FOR WEB SECURITY

I write this inorder to help my fellow to set up lab for web security issues let's go together

First you must have firefox and burpsuite installed in your machine.
Download Burp-Suite at > https://portswigger.net/burp/communitydownload
But firefox is already installed by default in kali linux but in window you must downloads in official page > https://www.mozilla.org/en-US/firefox/windows/

After you make sure those aplication have been installed in machine then use terminal to check the loopback ip address for your machine that allow you to connect locally within machine like this:

> Open terminal and type ifconfig
> 
> ![lo](https://hackmd.io/_uploads/BylmV1Scja.png)
> 
> so this show my local ip address is 127.0.0.1 that help me to connect locally.

Then open firefox and click on Menu TAB > Settings > Network settings > Setting > Add local IP Address

> Follow the Screenshot
> 
> ![Screenshot_2024-02-14_16_27_15](https://hackmd.io/_uploads/HyLMMr5jp.png)
> 
> You can search for Network Settings At the search bar
> 
> ![Screenshot_2024-02-14_16_28_03](https://hackmd.io/_uploads/HJEfGrqj6.png)


> Or you can scroll till down to see the network settings and once you found it click on Settings in order to configure
> 
> ![Screenshot_2024-02-14_16_28_16](https://hackmd.io/_uploads/r14zfHcja.png)
> 
> After you open the Settings it will open the tab like this then add locally ip address > 127.0.0.1 on port side add 8080.
> 
> ![Screenshot_2024-02-14_16_28_37](https://hackmd.io/_uploads/S1EGzr5sT.png)


So after after finish to add this in firefox then you must add Certification for burp suite that will not guide you to visit in site untill you verify that you trust the link.
Download the certification from burp suite open this url:
> hhtp://burp/ 
> http://localhost:8080/
> 
> ![Screenshot_2024-02-14_16_48_49](https://hackmd.io/_uploads/B1s_SBcip.png)
> 
> Once you have clicked on CA certificate

Then open the Downloads Directory and you will see something like 
![Screenshot_2024-02-14_16_54_05](https://hackmd.io/_uploads/rkg_IS9sa.png)


Open firefox > TAB MENU > Settings > Privacy and Security > Certificate

![Screenshot_2024-02-14_16_59_32](https://hackmd.io/_uploads/Sk0V_rqja.png)

You can search for the term certificate 

![Screenshot_2024-02-14_17_00_50](https://hackmd.io/_uploads/rkREOS9jp.png)

Also you can scrolldown to certificate and click on view certificate

![Screenshot_2024-02-14_17_01_24](https://hackmd.io/_uploads/ry1ruBcjT.png)


After click on view certificate it will open the dialog that will allow you to import file then choose import choose file you have download from burp certificate page

![Screenshot_2024-02-14_17_07_18](https://hackmd.io/_uploads/ryeIYH9sa.png)



![Screenshot_2024-02-14_17_07_32](https://hackmd.io/_uploads/SkbLKHqja.png)

After import click Ok then come to firefox and make sure you start burp suit and intercept is on then search for google.com you will see the result.

![Screenshot_2024-02-14_17_10_23](https://hackmd.io/_uploads/SycSqrco6.png)


![Screenshot_2024-02-14_17_10_39](https://hackmd.io/_uploads/ry_Pqr9j6.png)



![Screenshot_2024-02-14_17_10_48](https://hackmd.io/_uploads/rkQYqSqo6.png)


click on the forward button in burp suite until the google.com appear in the webpage so now you have already configure to work with firefox

![Screenshot_2024-02-14_17_11_26](https://hackmd.io/_uploads/BkA1oBqja.png)

Thanks! 


