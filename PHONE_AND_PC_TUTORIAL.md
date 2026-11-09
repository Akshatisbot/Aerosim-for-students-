# AeroSim setup tutorial 📱💻

This guide shows how to download, organise and run AeroSim on a computer or Android phone.

## 1. Download the project

1. Open the [AeroSim GitHub repository](https://github.com/NeonPhobiaStudios/Aerosim-for-students-).
2. Tap or click **Code → Download ZIP**.
3. Extract the ZIP using your computer's or phone's file manager.

**Note:** This repository is currently private. You must be signed in to an account with access to download it.

## 2. Check the folder structure

After extracting, open the project folder. It should contain:

```text
Aerosim-for-students-/
├── index.html
├── style.css
├── app.js
├── README.md
└── PHONE_AND_PC_TUTORIAL.md
```

Keep `index.html`, `style.css` and `app.js` together in this same folder. Do not rename or separate them.

## 3. Run AeroSim on a PC or laptop

1. Open the extracted `Aerosim-for-students-` folder.
2. Find `index.html`.
3. Double-click it.
4. If asked, choose Chrome, Edge or Firefox.

AeroSim should open as a webpage. No Python, Node.js or extra libraries are needed.

## 4. Run AeroSim on an Android phone

### Option A: use a code editor with HTML preview

1. Download the ZIP from GitHub and extract it with your phone's file manager.
2. Open a code editor that supports HTML preview, such as Acode.
3. Open the extracted `Aerosim-for-students-` folder in the editor.
4. Open `index.html`.
5. Use the editor's **Preview** option.

The exact menu names can vary between editor versions. Keep the three main files together.

### Option B: use GitHub Pages

GitHub Pages can publish the project as a website, but availability for a private repository depends on your GitHub plan and repository settings.

If Pages is available:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch `main` and folder `/(root)`.
5. Save and wait for GitHub to publish the site.
6. Open the website URL shown in Pages settings.

If Pages is unavailable for this private repository, use Option A. Do not assume the website is live until GitHub confirms a successful deployment.

## 5. What the files do

| File | Purpose |
|---|---|
| `index.html` | Page structure and simulator controls |
| `style.css` | Design and responsive layout |
| `app.js` | Lift, drag and graph calculations |
| `README.md` | Project introduction |
| `PHONE_AND_PC_TUTORIAL.md` | This guide |

## 6. Troubleshooting

- **No styling:** check that `style.css` is beside `index.html`.
- **Sliders do not work:** check that `app.js` is beside `index.html`.
- **GitHub says 404:** sign in and confirm that your account has access to this private repository.
- **Old version appears:** refresh the browser or close and reopen the tab.

## Accuracy note

AeroSim is an educational approximation, not a real aircraft design, flight-planning or safety tool.
