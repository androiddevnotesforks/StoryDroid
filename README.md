# StoryDroid
We have made the source code and the corresponding dataset publicly available. We hope this project can benefit other researchers or practiontiners in the field of analysis of Android apps. Please feel free to contact us (senchen@tju.edu.cn) if you have any questions and issues. We will continue to maintain this project. Thanks for your feedback.

## Environment Configuration
* Ubuntu/Macbook
* Python: 2.7
* APKTool: 2.4.1
* Android emulator：X86, Android 7.1.1, Google APIs, 1920 * 1080
* Android environment: adb, aapt
* Java environment (jdk): jdk1.8.0_45
* pip install opencv-python==3.4.3.18
* IC3: https://github.com/siis/ic3, please take the tool into the path /StoryDroid/main-folder/
* jadx: https://github.com/skylot/jadx, please take the tool into the path /StoryDroid/main-folder/
* libs support: Please take the android.jar files of all the different platform versions (android-3~android-32) into the path /StoryDroid/main-folder/config/libs/android-platforms/
* Open ~/.bashrc and configure the path of JDK and SDK (Replace by your own paths):
```
export JAVA_HOME=/usr/lib/jvm/jdk1.8.0_45
export JAVA_BIN=/usr/lib/jvm/jdk1.8.0_45/bin
export CLASSPATH=.:${JAVA_HOME}/lib/dt.jar:${JAVA_HOME}/lib/tools.jar
export PATH=$PATH:${JAVA_HOME}/bin
export PATH=$PATH:/home/dell/Android/Sdk/tools
export PATH=$PATH:/home/dell/Android/Sdk/platform-tools
export PATH=$PATH:/home/dell/Android/Sdk/emulator
export JAVA_HOME JAVA_BIN CLASSPATH PATH 
```

## Usage
```Python run_storydistiller.py [apk(s)_folder]```

## Website and Dataset
https://sites.google.com/view/storydistiller/

## Papers
[1] StoryDroid: Automated Generation of Storyboard for Android Apps (Research Paper)
```
@inproceedings{chen2019storydroid,
  title={Storydroid: Automated generation of storyboard for Android apps},
  author={Chen, Sen and Fan, Lingling and Chen, Chunyang and Su, Ting and Li, Wenhe and Liu, Yang and Xu, Lihua},
  booktitle={2019 IEEE/ACM 41st International Conference on Software Engineering (ICSE)},
  pages={596--607},
  year={2019},
  organization={IEEE}
}
```

[2] Automatically Distilling Storyboard with Rich Features for Android Apps (Research Paper)
```
@inproceedings{chen2022storydistiller,
  title={Automatically Distilling Storyboard with Rich Features for Android Apps},
  author={Chen, Sen and Fan, Lingling and Chen, Chunyang and Liu, Yang},
  booktitle={IEEE Transactions on Software Engineering (TSE)},
  year={2022},
  organization={IEEE}
}
```

[3] StoryDroid+: An Offline Tool for Generating Storyboard for Android Apps (Demo Paper, Under Submission)
```
@inproceedings{zhang22storydroid+,
  title={StoryDroid+: An Offline Tool for Generating Storyboard for Android Apps},
  author={Zhang, Yuxin, Chen, Sen and Fan, Lingling and Chen, Chunyang and Liu, Yang},
  pages={1--5},
  year={2022},
  organization={ACM}
}
```
## Contact
[Sen Chen](https://sen-chen.github.io/) All Copyright Reserved.
