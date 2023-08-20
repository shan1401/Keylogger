# Keylogger

Keyloggers are either software programs or hardware devices that track the activities of a keyboard. Keyloggers are a form of malware where users are unaware their actions on the keyboard are being tracked. Keyloggers can be used for a variety of purposes; hackers may use them to maliciously gain access to one's private information such as credentials. Some keyloggers can also capture your screen at random intervals; these are known as screen recorders. Keylogger software typically stores your keystrokes in a small file, which is either accessed later or automatically emailed to the person monitoring your actions. Keyloggers are used in everything from Microsoft products to your own employer’s computers and servers. Sometimes hackers implant legitimate websites, apps, and even USB drives with keylogger malware. First, we’ll further define keystroke logging before diving into how keyloggers work. This way, we can better understand how to secure ourselves. And we will implement the keylogger and understand it on a source code level so we can further identify and analyze this type of malware and protect our organization or ourselves from attacks on our privacy like these.

1. Initially we run the code in Intellij IDE and immediately we receive a warning from Windows Defender that our system is subject to a keylogger attack
2. Following this our code gets deleted from the IDE as a security response
3. Next, we disable the security from Virus and Threat Protection in Windows Defender and once
again run the code in the IDE
4. This time the code fruns successfully and everything we type is printed and is simultaneously
logged into the log.txt file which is created.
5. Once the code is run we can manually stop it or it will terminate after a stipulated time.
6. Further, we should switch on the Virus and Threat Protection in Windows Defender so that we
cn protect our system from future attacks and enable our security functions.


With our project, we have successfully implemented and analyzed the inner workings of a Keylogger and how it is used to capture unsuspecting users' keystrokes.
We would now be able to able to analyze this kind of malware when auditing various application source codes in the future as we have now implemented it ourselves and learned what it is made of.
In the future, we could work on how a Keylogger is employed in conjunction with a RAT with more keylogger functionalities to have a deep understanding of this kind of malware and better defend our organization from attacks.
