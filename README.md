# manage-my-life
AI tools to manage my life!

## Skills
Ready-to-use skills developed externally. Download the zip file of the repo periodically and add them to this repo to keep the skill updated.

| Skill | Use case |
| :--- | :--- |
| [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) | Create new skills |
| [SkillSpector](https://github.com/NVIDIA/SkillSpector) | Security scanner for skills before installation |

## Setup

### 1. Access the repo
To access the repo for the first time: 
1. Download [Visual Studio Code](https://code.visualstudio.com/download): VS Code is a code editor used to write code, create skills and agents, and publish changes to the repo
2. Create a GitHub account: GitHub contains the repo (think: cloud storage) that the AI skills and agents will be saved to and is shareable with others. Sign in to the account in VS Code.
3. [Generate a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent): The SSH key enables a linkage between the GitHub repo and your local VS Code, so that you can pull the latest version of the repo and push changes to it.
4. [Add the SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account): Link the SSH key you created in your local computer to your GitHub account.
5. [Clone the repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository): The repo is cloned to your VS Code so that you can make changes to it locally while keeping the version in GitHub intact until you're ready to push new changes to it.
6. Open the repo in VS Code: Locate the cloned repo at /Users/youruser and open the file location in VS Code to start editing.

### 2. Update the repo
After making changes to the repo in VS Code, go to the Source Control tab, and select:
1. 'Pull' to pull the latest version of the repo
2. 'Commit & Push' (with a message) to commit changes to the repo