# Contributing

We want to let you make the Catalog better! If you spot an issue with a gear item, you can fix the bug yourself and send us your fix. If we accept your change it will be published to the catalog!

## Finding bugs

Before you start trying to fix a bug, you should verify that the problem is caused by the gear item and not your game. To do this you should test in a place with just a baseplate and whatever else is necessary to reproduce the issue.

# Getting Started

### Set up GitHub Desktop
1. Download and install [Github Desktop](https://desktop.github.com/).
2. In the top right corner of the application, click the gear icon.
3. Click **Add account**.
4. Log in with your GitHub credentials.

### Fork and clone the repository
1. In a web browser, navigate to https://github.com/Roblox/Catalog.
2. In the top right corner of the page, click Fork.
3. On the right side of the page, click **Clone or download**.
4. Click **Open in Desktop** to clone the repository and open it in GitHub Desktop.
5. In GitHub Desktop, after verifying the name and location on your hard drive where you'd like to clone the repository, click **Clone**.
6. Now we are going to create a branch of the repository. Click the branch icon to the left of **master**.
7. Choose a descriptive name for your branch. In this case we will choose **gravity-coil-fix**.

# Fixing bugs

### Open the gear in Roblox Studio
3. In GitHub Desktop, right-click the **Catalog** repository.
4. Select **Open in Explorer**.
5. In Windows Explorer, open the **Items** directory and then the **Gear** directory.
1. Open Roblox Studio and make a new place.
2. Find the URL of a gear you are going to fix e.g. https://www.roblox.com/catalog/16688968/Gravity-Coil.
3. Copy the gear ID from the URL e.g. **16688968**.
4. In Windows Explorer, go to the gear directory.
5. Select the search box and paste the gear ID into the search box.
6. When the gear file appears in search results, drag the file into Roblox Studio.

### Fix the bug
Now is the part where you actually fix the bug. Try to avoid making unecessary changes (e.g. renaming variables) because it will make it harder to review your changes and less likely that they will be accepted.

### Test your changes
Once you are done making your changes, you need to test your gear in Studio to make sure it works properly. Select the **Test** tab in Studio and click **Start**. You must not use the **Play** testing mode because it is not as accurate as testing with a local server.

#### Testing Checklist
* Make sure the gear does not add unecessary lines to output. This means errors, warnings, and print statements.
* Test that the gear works with and without filtering enabled, and with both R15 and R6 characters.

### Save your changes
1. Once you are done testing, right-click the gear in Roblox Studio and select "Save to File...".
2. Navigate to the gear directory and select the gear file.
3. Click **Save**.
4. In GitHub Desktop you can see what changes you made to the gear file on the **Changes** tab.
5. If you made accidental changes e.g. adding extra whitespace you can undo those changes and re-save the gear from Roblox Studio.
6. Write a concise summary and description for what you changes. In this example the summary is "Fix Gravity Coil texture" and the description is "The texture is using an unsupported BMP format".
7. Click **Commit to gravity-coil-fix**.
8. In the top right corner, click **Pull request** to ask for your changes to be submitted for review.