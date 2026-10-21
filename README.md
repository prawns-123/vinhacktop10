# 🌱 STUDY GARDEN: Focus & Wellbeing Dashboard
**Grow Your Focus. Nurture Your Wellbeing.**
Study Garden is an interactive study productivity and wellbeing dashboard that brings study planning, focus tracking, academic assistance, and relaxation tools together in one place.
Designed for students, the platform encourages consistent study habits through a focus timer, a subject-based planner, visual study analytics, and a customizable Focus Guard.
🌐 **Live Website:** https://prawns-123.github.io/vinhacktop10/
## 🎯 Project Objective
The objective of Study Garden is to make studying more organized and engaging by providing students with tools to manage their time, track their study activity, organize academic tasks, and take intentional breaks.
Instead of switching between multiple tools, students can access their study timer, planner, analytics, document reader, and academic assistance from a single dashboard.
## ✨ Features
### 1. ⏱️ Study Timer & Break Management

* Switch between focus and break modes.
* Start, pause, and reset study sessions.
* Select an active subject for each session.
* Monitor continuous focus time and accumulated break time.
* Trigger an immediate break when needed.

### 2. 📅 Study Planner & To-Do Checklist

* Add academic tasks to a personalized checklist.
* Associate tasks with subjects.
* Track task completion and overall progress.

### 3. 📊 Study Analytics & Heatmap

* View a 24-hour daily study timeline.
* Explore study activity through a 30-day, 24-hour heatmap.
* Filter the heatmap by subject or view overall activity.
* Switch between different heatmap cell sizes.
* View monthly study totals, peak study hours, daily averages, and the most focused day.
* Use the built-in month simulation controls to explore sample study data.

### 4. 🎯 Attention Score Dashboard

* View an attention score and focus classification.
* Monitor displayed indicators for gaze direction, posture alignment, drowsiness, and screen switching.
* View the dashboard's focus and presence status indicators.

### 5. 📷 Camera-Based Monitoring Interface

* Enable the live camera through the browser.
* View the camera feed within the dashboard.
* Access camera-related focus indicators and alerts.
* Use the calibration control and Gemini AI audit interface.

**Note:** The presence of these interface elements does not by itself establish that every attention metric is measured accurately. Actual detection capabilities depend on the underlying implementation and any required external services.

### 6. 🔒 Customizable Focus Guard

* Set a continuous study target.
* Monitor progress toward the focus target.
* Keep the relaxation directory locked until the target is reached.
* Access relaxation resources after unlocking the directory.

### 7. 📚 Local File Launcher & Document Reader

* Select supported local files, including PDFs, Word documents, text files, Markdown files, and images.
* Select a local folder through the browser's file picker.
* Add file paths through the provided input.
* Open supported documents through the built-in viewer.
* Manage the displayed local file list.

**Note:** Local file access is subject to browser permissions and file-handling support. Adding a file path does not automatically grant a website unrestricted access to the user's filesystem.

### 8. 🤖 AI Academic Doubt Solver

* Access an academic assistance interface for study-related questions.
* Use the Gemini integration for academic help.
* Configure the Gemini API key through the provided interface.
* Clear the conversation when needed.

AI functionality requires the appropriate API configuration and network access.

### 9. 🌿 Break & Relaxation Directory

* Access linked relaxation resources such as YouTube, JioSaavn, Aha Health, and Lichess.
* Use the Focus Guard to regulate access to these resources.
* Trigger a short rest break from the dashboard.

### 10. 👥 Virtual Study Group

* View a dashboard showing virtual study peers.
* Display example subjects, study durations, and activity statuses.
* View the current user's displayed study status.

The peer information shown in the interface should not be interpreted as a live, synchronized multi-user service unless a corresponding backend or real-time integration is implemented.

### 11. 🌟 Personalization & Desk Mode

* Edit the daily motivational motto.
* Customize the daily study goal.
* Add target exam countdowns.
* Switch to a simplified desk mode.
* Interact with the dashboard's customizable controls.

---

## 🛠️ Technology Stack

| Technology         | Purpose                                                                                                                          |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| HTML5              | Structures the dashboard, forms, buttons, and content sections.                                                                  |
| CSS3               | Provides custom styling, layouts, transitions, and visual effects.                                                               |
| Tailwind CSS       | Provides utility-based styling and responsive layout classes. Loaded through the Tailwind CDN.                                   |
| Font Awesome 6.5.1 | Supplies icons used throughout the interface.                                                                                    |
| Google Fonts       | Provides the Plus Jakarta Sans and JetBrains Mono typefaces.                                                                     |
| Google Gemini API  | Provides AI academic assistance and the Gemini-related audit functionality, subject to the implementation and API configuration. |
| Git & GitHub       | Supports source-code hosting and version control.                                                                                |
| GitHub Pages       | Hosts the published website.                                                                                                     |

### Architecture

Study Garden is a **frontend-focused web application** built around HTML, CSS, and client-side JavaScript.
It uses external CDN resources for its styling framework, fonts, icons, and mathematical rendering library. Gemini-powered functionality requires API configuration.
The project does not require a custom backend for its basic dashboard interface. Any feature requiring an external AI service depends on that service being available and correctly configured.
### Prerequisites

* A modern web browser.
* An internet connection for external CDN resources and online integrations.
* A code editor such as Visual Studio Code (optional).

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/prawns-123/vinhacktop10.git
   ```

2. Open the downloaded project folder.

3. Locate the main HTML file.

4. Open the HTML file in a browser, or use the Live Server extension in Visual Studio Code.

5. Explore the dashboard and its available controls.

### AI Configuration

The AI Academic Doubt Solver requires a valid Gemini API key and network access.

Use the key configuration interface provided by the application.

**Security recommendation:** Avoid committing API keys to a public repository. A key embedded in frontend code or entered into a browser-based application cannot be treated as a secret. For a public deployment, use appropriate API restrictions and consider a secure server-side integration if stronger key protection is required.

---

## 📱 Responsive Design

The dashboard uses responsive layout utilities and different grid configurations to adapt its interface to varying screen widths.

The layout is intended to support both desktop and mobile use. Actual responsiveness should be verified on different devices and screen sizes.

---

## 🌐 Deployment

The website is published using GitHub Pages.

**Live Website:** https://prawns-123.github.io/vinhacktop10/

**Repository:** https://github.com/prawns-123/vinhacktop10

---

## 🔮 Future Enhancements

Potential future improvements include:

* Persistent storage for study history, tasks, and preferences.
* Secure handling of AI API credentials.
* More robust camera-based attention detection and validation.
* Real-time synchronization for virtual study groups.
* Exportable study reports and analytics.
* Additional accessibility and mobile usability improvements.

These are proposed enhancements, not claims about existing functionality.

---
## 📌 Project Scope

Study Garden focuses on frontend development, interactive UI design, productivity tools, and browser-based academic assistance.
Its core dashboard is implemented using HTML, CSS. External integrations, including Gemini-powered features, depend on their respective configuration and availability.
