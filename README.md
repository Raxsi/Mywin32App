# Windows Basic App

A simple Win32 desktop application demonstrating menus, modal dialogs, and modeless dialogs.

## Features
- Menu with File/Open, Exit
- About dialog (modal)
- Custom modeless dialog

## Build
Open the solution in Visual Studio and build.

## Next Steps
- Add controls (buttons, edit boxes) in dialogs
- Handle user input
- Expand to MFC-like structure
## 📂 Project Structure
WindowsBasicApp/
│
├── src/ # Source files (.cpp)
│├── main.cpp # Entry point (WinMain)
│├── MyDialog.cpp # Dialog proc
│└── resource.h # Resource IDs
│
├── include/ # Header files
│ └── MyDialog.h
│
├── res/ # Resources (RC, icons, manifests)
│ ├── WindowsBasicApp.rc
│ ├── app.ico
│ └── dialogs.rc
│
├── build/ # Build output (ignored in git)
│
├── WindowsBasicApp.sln # Visual Studio solution
├── .gitignore
└── README.md




yaml
Copy code
