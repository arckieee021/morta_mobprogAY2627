Laboratory Activity 0A: Flutter Installation and Project Setup

Student Name: Morta, Marvish Jerrime
Section: INF246
Date: November 11, 2026

Laboratory Discussion
1. What challenges did you encounter while installing or configuring Flutter?

During the installation and configuration of Flutter, I encountered several issues involving the Windows environment variables. Initially, Flutter could not find Git in the system PATH. After resolving that issue, I encountered another error because PowerShell was not properly configured in the PATH. I also had difficulty running Flutter commands because I was initially using the wrong working directory.

2. Did you encounter any errors when running flutter doctor?

Yes. Initially, Flutter reported that Git and PowerShell could not be found. After fixing the PATH configuration, Flutter successfully initialized and downloaded the required Dart SDK and dependencies. The Flutter Doctor command also indicated that the Android SDK and Visual Studio were not installed.

3. How did you resolve installation, dependency, SDK, or device-related issues?

I resolved the Git and PowerShell errors by checking their installation directories and adding the correct paths to the Windows environment variables. I restarted my terminal and tested the commands again. I also navigated to the correct Flutter project directory before running Flutter commands. Since Chrome was available as a connected device, I used it to run and test my application.

4. What did you learn about configuring a Flutter development environment?

I learned how to install and configure Flutter, Dart, Git, and Visual Studio Code. I also learned how to use Flutter commands such as flutter doctor, flutter devices, flutter pub get, and flutter run. This activity helped me understand the importance of environment variables, project directories, and development tools.

5. What practices will you follow to make future Flutter development easier?

I will regularly check my Flutter and Dart SDK versions, keep my development tools updated, organize my project directories properly, and use GitHub to manage my source code. I will also test my applications regularly, read error messages carefully, and consult official documentation whenever I encounter problems.

Project Information
Project Directory: morta_mobprogAY2627
Flutter Application: morta_mobprog
Framework: Flutter
Programming Language: Dart
Testing Device: Google Chrome
Application Output: Hello World!