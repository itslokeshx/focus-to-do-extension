# ⏱️ Focus To-Do Extension (Offline Build)

A local-first, offline-ready build of the Focus To-Do browser extension.

This project is intended for users who want core task and Pomodoro functionality without depending on a cloud account.

## 🚀 Highlights

- Works fully offline
- Includes core task management features
- Includes Pomodoro focus timer workflow
- Stores data locally in browser storage
- No server setup required

## ✅ Included Features

### Task Management

- Create and edit tasks
- Mark tasks complete
- Organize task lists
- Track daily productivity

### Pomodoro Timer

- Start/stop focus sessions
- Run short and long breaks
- Track focus duration over time

### Local Data Persistence

- Data is saved in local browser storage
- Fast access with no network dependency

## ⚠️ Not Included in This Build

Because this is an offline-first build, these features are not available:

- Cloud sync
- Account login
- Cross-device synchronization
- Remote backup/recovery

If browser storage is cleared, local data may be lost.

## 🏗️ How It Works

```
Browser Extension
        ↓
Task + Timer UI
        ↓
Local Storage Layer (IndexedDB / browser storage)
        ↓
Data stays on your device
```

## 📁 Project Structure

```
focus-to-do-extension/
├── WebContent/      # Main UI and scripts
├── _locales/        # i18n translation files
├── images/          # Icons and static assets
├── background.js    # Extension background logic
├── manifest.json    # Extension manifest
├── LICENSE
└── README.md
```

## ⚙️ Installation (Chrome)

1.  Clone the repository:

        ```bash
        git clone https://github.com/itslokeshx/focus-to-do-extension.git
        ```

2.  Open Chrome Extensions:

        ```
        chrome://extensions
        ```

3.  Enable **Developer mode** (top-right).
4.  Click **Load unpacked**.
5.  Select the `focus-to-do-extension` folder.

The extension should now load and run locally.

## 🔒 Privacy

This build is designed to be local-first:

- No analytics pipeline included
- No user-tracking service included
- No required remote API for core usage

Your data remains on your device unless you export or sync it using your own tools.

## 🧠 Optional Self-Hosted Sync Backend

If you need backup and sync, you can pair this extension concept with a separate self-hosted backend project:

- Repository: [Second Brain](https://github.com/itslokeshx/Second-Brain)
- Live app: [second-brain-hub.vercel.app](https://second-brain-hub.vercel.app/)

## ⚖️ Attribution

This repository is a modified build.

- The original Focus To-Do product, branding, and design rights belong to their respective owners.
- This repository is maintained for educational/local-use customization purposes.

## 👤 Maintainer

- Lokesh
- GitHub: [itslokeshx](https://github.com/itslokeshx)

## ⭐ Support

If this project helps you, please consider starring the repository.
