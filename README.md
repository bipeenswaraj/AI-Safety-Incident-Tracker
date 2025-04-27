# AI Safety Incident Tracker

## Description
The **AI Safety Incident Tracker** is an Android app that tracks AI safety incidents. It allows users to view, filter, and report AI-related incidents. The app supports features like:
- **Viewing a list of incidents** with title, severity, and date.
- **Filtering incidents** based on severity.
- **Detailed incident view** with full information.
- **Reporting new incidents** with title, description, and severity.

## Features
- **Incidents List**: Displays a list of incidents with basic details.
- **Filter by Severity**: Filter the incidents by their severity level.
- **Detailed View**: View detailed information about an incident when tapped.
- **Report Incident**: Allow users to report new incidents.

## Prerequisites

To build and run this project locally, you’ll need the following:

- **Android Studio** (Recommended version: 4.1+)
  - [Download Android Studio](https://developer.android.com/studio)
  
- **Java Development Kit (JDK)** (Version 8 or above)
  - [Download JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

- **Kotlin** (This project is written in Kotlin)
  - [Install Kotlin](https://kotlinlang.org/docs/tutorials/command-line.html)

## Installation

### Clone the Repository

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your_username/AI-Safety-Incident-Tracker.git
Navigate into the project folder:

bash
cd AI-Safety-Incident-Tracker

Open Android Studio.

Select Open an Existing Project.

Navigate to the folder where you cloned the repository and select it.

Android Studio will automatically download any necessary dependencies.

Install Dependencies
The project uses Gradle to manage dependencies. Gradle will automatically download the dependencies when you sync the project. Follow these steps to sync the project:

In Android Studio, click Sync Now when prompted to sync the Gradle files.

If no prompt appears, go to the File menu and select Sync Project with Gradle Files.

Build the Project
Once dependencies are synced, you can Build the project by going to the Build menu and selecting Build Project.

If the project builds successfully, you can run it on an emulator or physical device.

Running the Project
Run on Emulator
To run the project on an Android emulator, click on the Run button (Green triangle) in Android Studio.

Select an available virtual device (or create a new one if needed).

Run on Physical Device
Connect your Android device via USB and enable Developer Mode and USB Debugging on your device.

In Android Studio, select your connected device from the available options.

Click on the Run button to install and launch the app on your device.

Technologies Used
Kotlin for the main app code.

RecyclerView for displaying a list of incidents.

FloatingActionButton for adding new incidents.

Firebase (Optional) for backend integration (if applicable).

Android SDK for building the app.

Folder Structure
app/: Contains the source code of the app.

res/: Contains resources like layouts, images, and strings.

build.gradle: Contains project dependencies and build configurations.

settings.gradle: Contains the project settings.

AndroidManifest.xml: Contains app-level configurations.

Contributing
If you'd like to contribute to this project, feel free to fork the repository and make your changes. Create a pull request with a description of what you’ve done.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

### What to Do Next:

1. **Open your GitHub repository**.
2. **Create a `README.md` file** if you don't have one already.
3. **Copy and paste** the content above into the `README.md` file.
4. **Commit the changes** to your repository:

```bash
git add README.md
git commit -m "Added README file with installation instructions"
git push origin master
Explanation:
The Installation section includes all the necessary steps for setting up Android Studio, cloning the repository, installing dependencies, and building the project.

The Running the Project section explains how to run the app on both an emulator and a physical device.

The Technologies Used section provides an overview of the tools and frameworks used in the project.

The Folder Structure section helps users understand how your project is organized.

