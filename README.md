# Easy NetBanking 💳

An AI-assisted Android application designed to simplify personal finance management through transaction tracking, savings goals, financial challenges, and conversational AI assistance.

## 📌 Project Information

- **Project Name:** Easy NetBanking
- **Domain:** Artificial Intelligence and Machine Learning
- **Platform:** Android
- **Institution:** Sathyabama Institute of Science and Technology, Chennai, India

### 👨‍💻 Team Members

| Name | Register Number |
|---|---|
| Suhail Ahmed | 44611353 |
| Mohammad Anas | 44611350 |

**Project Guide:** Dr. R. Rajalakshimi

## ✨ Features

- **Personal Finance Management:** Organize and manage personal financial records.
- **Transaction Tracking:** Add and manage transaction information.
- **Savings Goals:** Set financial targets and track progress.
- **Financial Challenges:** Support goal-oriented financial habits.
- **AI Financial Copilot:** Interact with an AI assistant for general financial explanations and planning support.
- **Local Data Storage:** Use Room database for supported locally stored data.
- **Modern Android UI:** Build the interface with Jetpack Compose.
- **Error Handling:** Design for loading states and remote-service failures.

*Feature availability depends on the current implementation and configuration of the project.*

## 🛠️ Technology Stack

- Kotlin
- Android SDK
- Jetpack Compose
- Android Jetpack ViewModel
- Room Database
- Retrofit / HTTP networking, where configured
- Generative AI API integration, where configured
- Android Studio
- Gradle

## 🏗️ System Architecture

The application follows a layered architecture:

1. **Presentation Layer:** Displays screens and handles user interaction.
2. **ViewModel Layer:** Manages screen state and coordinates user actions.
3. **Repository Layer:** Separates data operations from the UI.
4. **Local Database Layer:** Stores supported records using Room.
5. **AI Service Layer:** Communicates with a remote AI service when configured.

## 🚀 Getting Started

### Prerequisites

- A Windows, macOS, or Linux computer
- Android Studio
- A compatible Android SDK
- Internet access for downloading dependencies and using online AI features
- An AI API key if required by the configured AI integration

### Installation

1. Clone or download this repository.
2. Extract the project if you downloaded a ZIP file.
3. Open Android Studio.
4. Select **Open** and choose the project folder containing the Gradle project files.
5. Allow Gradle sync and dependency downloads to finish.
6. Configure any required API credentials using the project's expected configuration method.
7. Connect an Android device with USB debugging enabled or start an Android emulator.
8. Select **Run ▶** in Android Studio.

**Note:** Build requirements may vary depending on the project's Gradle and Android SDK configuration.

## 🔐 Security and Privacy

- Never commit API keys, passwords, signing keys, or other secrets to GitHub.
- Use a secure configuration method for API credentials.
- Avoid logging sensitive financial information.
- Review data handling and third-party AI processing before using real personal data.
- Test authentication, persistence, network errors, and permissions before release.

## 🧪 Testing

Before a release, test:

- Application launch and navigation
- Transaction and savings-goal operations
- Local data persistence after restarting the app
- Invalid inputs and error states
- AI requests, connectivity failures, and invalid responses
- Accessibility and supported Android versions

## ⚠️ Disclaimer

Easy NetBanking is an educational software project for personal finance management and AI-assisted interaction. Unless explicitly implemented and verified, it should not be considered a real banking application, a bank-certified service, or a system capable of executing bank transfers. AI-generated responses may be inaccurate and should not be treated as professional financial advice.

## 🔮 Future Enhancements

- Improved financial dashboards and reports
- More comprehensive testing and accessibility support
- Multilingual user experience
- Enhanced privacy controls
- Secure, authorized financial-data integrations where appropriate

## 📄 License

No license has been specified yet. Please add a license file before permitting others to reuse, modify, or distribute this project.

---

**Developed by Suhail Ahmed and Mohammad Anas**  
Department of Artificial Intelligence and Machine Learning  
Sathyabama Institute of Science and Technology, Chennai, India
