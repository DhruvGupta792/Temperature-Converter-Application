# Temperature-Converter-Application

This Java program creates a Temperature Converter application with a graphical user interface (GUI). Let me explain it in simple terms:

Import Statements:

These are like shortcuts to pre-made code (libraries) that help us create windows and buttons easily.
TemperatureConverterApp Class:

This is where the main code for the temperature converter is written.
Private Variables:

These are like containers that hold information for the program to use.
For example, temperatureField is where the user enters the temperature.
TemperatureConverterApp() Method:

This is a special method (constructor) that runs when we create a new TemperatureConverterApp.
It sets up the user interface (UI) with a window, buttons, and text fields.
Button Group:

celsiusToFarBtn and farToCelsiusBtn are radio buttons that let the user choose the conversion type.
We put them in a group so only one can be selected at a time.
Button Actions:

When the user clicks the "Convert" button, the program figures out which conversion to do based on the selected radio button.
Try-Catch Block:

This helps handle situations where the user enters something that's not a number. It prevents the program from crashing.
Calculations:

Based on the user's choice, the program does the temperature conversion math.
It then shows the result in the resultLabel.
Main Method:

This is where the program starts running. It creates an instance of TemperatureConverterApp, which opens the window.
Setting Up the Window:

setTitle, setSize, setDefaultCloseOperation, setLocationRelativeTo, and setVisible are commands that control how the window looks and behaves.
In simple terms, this program makes a window where you can choose between converting Celsius to Fahrenheit or Fahrenheit to Celsius. You enter the temperature, click "Convert", and it shows the converted result. If you enter something that's not a number, it will ask you to correct it.




