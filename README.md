# DVWA Security Lab - Web Pentesting Project

## Prerequisites: Install Docker (Linux / Kali)

\`\`\`bash
sudo apt update
sudo apt install docker.io docker-compose -y
sudo systemctl start docker
sudo systemctl enable docker
\`\`\`

## Setup Steps

1. Clone this repository:
\`\`\`bash
git clone https://github.com/mustafa-26sy/dvwa-lab-project.git
cd dvwa-lab-project
\`\`\`

2. Start the container:
\`\`\`bash
sudo docker-compose up
\`\`\`
(or `sudo docker compose up` depending on your installation)

3. Open your browser and go to:
\`\`\`
http://localhost
\`\`\`

4. Login credentials:
   - Username: `admin`
   - Password: `password`

5. Go to **Setup** page → click **Create / Reset Database**

6. Go to **DVWA Security** tab → select difficulty level (**Low** to start)

