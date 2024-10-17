This repository was done in order to test using github pages to host a game.

The attempt was successfull.

I used a general tutorial build that unity already provided.

These were the steps:
1. Build Your Unity Project for WebGL

(NOTE: You may want to do these steps first before building the WebGL files, since pages won't read the gz zip files that unity creates.
Open your Unity project.
Go to File > Build Settings.
Select WebGL and click on the Player Settings button.
In the Player Settings window, navigate to the Publishing Settings section.
Under Compression Format, select Disabled instead of Gzip or Brotli.)

    Open your Unity project.
    Go to File > Build Settings.
    Select WebGL as the platform and click Switch Platform.
    Click Build, choose a folder, and let Unity generate the WebGL build files.

2. Create a GitHub Repository

    Open GitHub Desktop.
    Click File > New Repository.
    Fill in the details (repository name, description, and local path) and set it as public. This will be the repository for your Unity WebGL project.
    Click Create Repository.

3. Add WebGL Build Files to Your Repository

    Navigate to the folder where you saved the Unity WebGL build files.
    Copy the contents of the build folder (which will include index.html, Build, and TemplateData).
    Paste these files into the folder where your local GitHub repository is located.

4. Commit and Push Changes Using GitHub Desktop

    In GitHub Desktop, you should see that the new files have been detected as changes.
    Write a commit message (e.g., “Add Unity WebGL build”).
    Click Commit to main.
    After committing, click Push origin to upload the changes to GitHub.

5. Enable GitHub Pages

    Go to your repository on the GitHub website (it will be located at https://github.com/<username>/<repository-name>).
    Click on the Settings tab in your repository.
    Scroll down to the Pages section (on the left menu or under "Code and automation").
    Under Source, select main branch and the root (/) directory, or you can select docs if you want to place your build files in a docs folder.
    Click Save.

6. To access the game you need to follow this convention: "https://<username>.github.io/<repository-name>/"
