# DVWA Security Lab - Web Pentesting Project

## Prerequisites: Install Docker Desktop (Windows)

1. Download Docker Desktop from:
https://www.docker.com/products/docker-desktop

2. Run the installer and follow the setup wizard
   - If prompted, enable **WSL 2** (Windows Subsystem for Linux) — the installer will guide you through this
   - Restart your computer if asked

3. Open Docker Desktop and make sure it's running (whale icon in the system tray)

## Setup Steps

1. Install Git for Windows (if not already installed):
https://git-scm.com/download/win

2. Open **Command Prompt** or **PowerShell**, then clone this repository:
\`\`\`bash
git clone https://github.com/mustafa-26sy/dvwa-lab-project.git
cd dvwa-lab-project
\`\`\`

3. Start the container:
\`\`\`bash
docker-compose up
\`\`\`

4. Open your browser and go to:
\`\`\`
http://localhost
\`\`\`

5. Login credentials:
   - Username: `admin`
   - Password: `password`

6. Go to **Setup** page → click **Create / Reset Database**

7. Go to **DVWA Security** tab → select difficulty level (**Low** to start)

