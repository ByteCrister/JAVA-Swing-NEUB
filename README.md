# Java Swing Components

### Overview

This repository contains a collection of Java Swing components and examples. It demonstrates the usage of various Swing elements to build graphical user interfaces (GUIs) in Java. These examples serve as a reference for understanding how to implement different Swing components, layout managers, and event handling in desktop applications.

---

## Table of Contents

1. [Repository Structure](#repository-structure)
2. [Components Covered](#components-covered)
3. [Prerequisites](#prerequisites)
4. [How to Use](#how-to-use)
---

## Repository Structure


Each folder contains Java files demonstrating specific Swing components and how to use them in a GUI.

---

## Components Covered

- **JButton**: 
    - Creating buttons for user interaction.
    - Adding action listeners to handle events when buttons are clicked.
    - Customizing button appearance with icons, colors, and fonts.
    - Supporting different button states (enabled/disabled).
    
- **JTextField & JTextArea**: 
    - Handling single-line input with `JTextField` and multi-line input with `JTextArea`.
    - Implementing event listeners to capture and process user input in real-time.
    - Customizing appearance and behavior (setting placeholder text, input length restrictions).
    - Integrating with other components for input validation or data submission.
    
- **JLabel**: 
    - Displaying text and images within a GUI.
    - Customizing text alignment, font styles, and colors.
    - Using labels as instructions or descriptions alongside input fields.
    - Displaying images with text, scaling, and managing icons.

- **JPanel**: 
    - Organizing components within a container using different layout managers.
    - Managing layouts such as `FlowLayout`, `BorderLayout`, `GridLayout`, etc., to control component placement.
    - Nesting panels to create complex, structured UIs.
    - Customizing the background color, borders, and visibility.

- **JMenu & JMenuBar**: 
    - Building menus for desktop applications with drop-down options.
    - Creating nested submenus, checkboxes, and radio button menu items.
    - Handling user selections through action listeners.
    - Organizing and grouping menu items logically, e.g., File, Edit, View menus.

- **JDialog**: 
    - Implementing modal and non-modal dialog windows for user interaction.
    - Customizing dialogs with different messages, input fields, and buttons.
    - Showing confirmation, error, and input dialogs using `JOptionPane`.
    - Adding event handling for dialog actions (e.g., OK, Cancel).

- **JTable**: 
    - Displaying tabular data in a grid format with rows and columns.
    - Supporting data manipulation (adding, updating, deleting rows).
    - Customizing table appearance (cell renderers, headers, row/column size).
    - Adding sorting and filtering functionality to manage large data sets.

- **JScrollPane**: 
    - Wrapping components like `JTextArea`, `JTable`, or large panels inside a scrollable viewport.
    - Allowing users to navigate large content by scrolling vertically or horizontally.
    - Customizing scroll bar behavior and visibility.

- **JTabbedPane**: 
    - Creating tabbed panes for organizing content into different tabs.
    - Allowing users to switch between multiple views within the same window.
    - Adding custom icons and tooltips to tabs.
    - Managing dynamic content updates when switching tabs.

- **JComboBox**: 
    - Creating drop-down menus for user selections.
    - Supporting custom objects in combo boxes (e.g., icons with text).
    - Handling selection events with listeners.
    - Customizing appearance and behavior (editable combo boxes for custom input).

- **JSlider**: 
    - Implementing sliders for selecting values within a defined range.
    - Supporting horizontal and vertical orientations.
    - Adding tick marks and labels to represent discrete values.
    - Customizing slider appearance and handling value changes with listeners.

- **JProgressBar**: 
    - Displaying progress for long-running tasks.
    - Supporting both determinate and indeterminate progress modes.
    - Customizing the appearance and color of the progress bar.
    - Integrating with background tasks to update progress dynamically.

- **JCheckBox & JRadioButton**: 
    - Implementing checkboxes for multiple selections.
    - Using radio buttons for mutually exclusive options (single selection).
    - Grouping radio buttons to ensure only one can be selected at a time.
    - Handling selection events and state changes with listeners.

- **JSpinner**: 
    - Providing a compact way for users to select numbers or values.
    - Customizing spinners with numeric ranges, dates, or custom objects.
    - Handling user input and ensuring valid values.
    - Integrating with other components for more advanced input handling.

---

## Prerequisites

- **Java Development Kit (JDK)**: Make sure Java is installed on your system. You can download it from [here](https://www.oracle.com/java/technologies/javase-downloads.html).
- Basic knowledge of Java and the Swing library.

---

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-swing-repo.git
    ```
2. Navigate to the specific component folder you want to explore.
3. Compile and run the Java file using:
    ```bash
    javac Filename.java
    java Filename
    ```

Each file demonstrates the use of a specific Swing component, and you can modify the code to suit your learning or project needs.
