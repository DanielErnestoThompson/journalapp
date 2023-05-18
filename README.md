**JournalApp - A Simple Journaling Desktop Application**

**Description**
JournalApp is a basic C# desktop application built with WPF that encourages users to journal by opening a journal prompt each time the computer starts. 
When opened, the application displays the current date, time, and a journal entry number, allowing users to log their thoughts, reflections, and experiences. 
Entries are automatically saved into a text file in the system's default Documents folder upon closing the application.

**Installation and Setup**

**Prerequisites**

1. .NET SDK: Download and install from https://dotnet.microsoft.com/download
2. Visual Studio Code: Download and install from https://code.visualstudio.com/download
3. C# extension for Visual Studio Code: Install from https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp

**Running the application**
Clone the repository and navigate to the project folder. Run the application using the .NET CLI:

-- dotnet run

**Autostart Configuration**
To have the application start every time the user logs in, a batch file (startApp.bat) is included. 
This file must be manually added to the Startup folder:

1. Press Win + R to open the Run dialog, type shell:startup, and press Enter. This opens the Startup folder.
2. Drag and drop the startApp.bat file into the Startup folder.

**Features**
- Automatically opens when the computer starts.
- Provides a text box for entering journal entries.
- Displays the current date, time, and a unique entry number for each journal entry.
- Automatically saves entries into a text file upon closing the application.

**Contributing**
Contributions are always welcome! Please read the contribution guidelines first.

License
This project is licensed under the MIT License.

Please note that you will need to adjust this template to match the actual structure and features of your application, as well as your project's contribution guidelines and license details.




