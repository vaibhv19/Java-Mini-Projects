# Paint GUI Application

A simple Java Swing-based drawing application where users can draw points of different colors on a canvas.

## Files & Their Roles

- **App.java**  
  Entry point of the application. Uses `SwingUtilities.invokeLater` to ensure GUI creation on the Event Dispatch Thread.

- **PaintGui.java**  
  Main window frame that sets up the GUI components like canvas and control buttons.

- **Canvas.java**  
  A custom JPanel that handles mouse input and draws colored points on the screen.

- **ColorPoint.java**  
  A simple data class representing a point's coordinates and its color.