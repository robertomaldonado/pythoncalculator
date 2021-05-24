The code has been taken as an example to learn about PyQt

All credits to Leodanos Pozo Ramos at Real Python: 
https://realpython.com/python-pyqt-gui-calculator/


Applications
The most basic class you’ll use when developing PyQt GUI applications is QApplication. This class is at the core of any PyQt application. It manages the application’s control flow as well as its main settings. In PyQt, any instance of QApplication is considered to be an application. Every PyQt GUI application must have one QApplication object. Some of the application’s responsibilities include:

Handling initialization and finalization
Providing the event loop and event handling
Handling most of the system-wide and application-wide settings
Providing access to global information, such as the application’s directory, screen size, and so on
Parsing common command-line arguments
Defining the application’s look and feel
Providing localization capabilities
