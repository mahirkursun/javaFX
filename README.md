# javaFX Tutorial 
JavaFX Tutorial

License

The code is provided under MIT License and the tutorial is provided under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

CC

Instillation and Setup
This tutorial uses IntelliJ IDEA and Java SE 8.

Setting up JDK
Mac
Download Java SE website and click on JDK download button, this will take you to next page.
Under Java SE Development Kit, read and accept the licence (like we all do ;p). Once accepted, download JDK for Mac OS X x64 and follow the instructions on the scree.
Setting up Scene Builder 2.0
Download JavaFX Scene Builder 2.0 for Max OS X.
Open the *.dmg file and move the scene builder to Applications folder.
That's it!
Setting up IntelliJ IDEA
Mac
Installing IDE
Go to IntelliJ IDEA and download the IDE.
Open the *.dmg file and move IntelliJ IDEA to Applications folder.
Open now moved application from Applications folder. If you have previously installed IDEA on your system import the settings of it else click on ok.
Set your default UI.
Select your keymap.
if you want to tune your IDE you can do in this step else click on Next.
Install these plugins IF you want to. Click on Start using IntelliJ
Setting up IDE to use JDK
Note: JDK is located in /Library/Java/JavaVirtualMachines/jdk1.8.0_51.jdk/Contents/Home/bin/java

Once you open the IDE, click on Create New Project.
If Project SDK (top of the application) is empty, click on New and click on JDK. Browse to the JDK location /Library/Java/JavaVirtualMachines/jdk1.8.0_51.jdk/Contents/Home/ and click on choose.
Then click on Cancel to close this pane.
Setting up IDE to use JavaFX Scene Builder
Once you open the IDE, on the bottom left of the pane click on Configure > Preferences.
On the left side of the pane, search for Languages & Frameworks > JavaFX, this will open JavaFX setting on the right pane.
In the blank space type in /Applications/JavaFX Scene Builder 2.0.app or use ... to browse to the application.
Once done click on Ok.
Fonts
Courtesy of

Font Awesome
daFont - Tron.
Structure
JavaFX
|
+-- src
|   |
|   +-- README.md
|   +-- HelloWorld_1
|   |   |
|   |   `-- main.java
|   +-- HelloWorldSceneBuilder_2
|   |   |
|   |   +-- g-4.jpg
|   |   +-- main.java
|   |   `-- Main.fxml
|   +-- ButtonsEvents_3
|   |   |
|   |   +-- README.md
|   |   +-- ButtonsEvents_3_1
|   |   |   |
|   |   |   +-- README.md
|   |   |   +-- controller.java
|   |   |   +-- main.java
|   |   |   `-- Main.fxml
|   |   +-- ButtonsEvents_3_2
|   |   |   |
|   |   |   +-- README.md
|   |   |   +-- controller.java
|   |   |   +-- main.java
|   |   |   `-- Main.fxml
|   |   `-- ButtonsEvents_3_3
|   |       |
|   |       +--- README.md
|   |       +-- controller.java
|   |       +-- main.java
|   |       `-- Main.fxml
|   +-- StyleSheet_4
|   |   |
|   |   +-- README.md
|   |   +-- Stylesheet_4_1
|   |   |   |
|   |   |   +-- README.md
|   |   |   +-- controller.java
|   |   |   +-- main.java
|   |   |   +-- main.css
|   |   |   `-- Main.fxml
|   |   `-- Stylesheet_4_2
|   |       |
|   |       +-- README.md
|   |       +-- controller.java
|   |       +-- main.java
|   |       +-- main.css
|   |       `-- Main.fxml
|   +-- ReadingTextField_5
|   |   |
|   |   +-- README.md
|   |   +-- ReadingTextField_5_1
|   |   |   |
|   |   |   +-- README.md
|   |   |   +-- controller.java
|   |   |   +-- main.java
|   |   |   `-- Main.fxml
|   |   `-- ReadingTextField_5_2
|   |       |
|   |       +-- README.md
|   |       +-- controller.java
|   |       +-- main.java
|   |       `-- Main.fxml
|   +-- Menu_6
|   |   |
|   |   +-- controller.java
|   |   +-- main.java
|   |   +-- README.md
|   |   `-- Main.fxml
|   +-- FileChooser_7
|   |   |
|   |   +-- controller.java
|   |   +-- main.java
|   |   +-- README.md
|   |   `-- Main.fxml
|   +-- CustomFonts_8
|   |   |
|   |   +-- controller.java
|   |   +-- main.java
|   |   +-- fontawesome-webfont.ttf
|   |   +-- TRON.TTF
|   |   +-- README.md
|   |   `-- Main.fxml
|   `-- Threading_9
|       |
|       +-- README.md
|       `-- JavaFXAndForLoops_9_1
|           |
|           +-- README.md
|           +-- controller.java
|           +-- looper.java
|           +-- main.java
|           `-- Main.fxml
`-- README.md
