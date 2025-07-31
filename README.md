# HUSTEG 2025 - Workshop | Automated Testing in CI/CD with Jenkins & GitHub Actions

Dear Participant,

I’m glad you chose my workshop :)

To verify the environment we'll be using during the workshop, please follow the steps outlined in the WORKSHOP INSTRUCTIONS section.

## WORKSHOP INSTRUCTIONS

Please make sure to arrive at the workshop with a **laptop** – preferably running **Windows**.  
Ensure that your laptop is not restricted by any limitations such as:

- lack of administrative privileges (required to install tools),
- restricted internet access (VPN, firewall, proxy, etc.).

---

### Prerequisites

Skills:
- Basic understanding of software testing and version control
- GitHub account and basic Git knowledge

Technical Prerequisites:

#### 1. Install VS Code IDE  
Download and install from:  
👉 https://code.visualstudio.com/download

#### 2. Install Java JDK (version 11 or newer)  
Download from:  
👉 https://www.oracle.com/java/technologies/downloads/  

After installation, open **CMD** and verify the installation:
```bash
java -version
javac -version
```
Both commands should return the installed JDK version.

#### 3. Install Python (version 3.13.2)  
Download from:  
👉 https://www.python.org/downloads/  

During the installation, make sure to **check the box**:  
✅ `Add python.exe to PATH`

Then, verify installation:
```bash
python --version
```
You should see the installed Python version.

---

### GitHub & Project Setup

#### 4. Fork the Repository  
Go to:  
👉 https://github.com/tklepacki/rest-api-tests-python  

Click **Fork** to create a copy in your GitHub account.

> ℹ️ Don’t have a GitHub account? Create one first at https://github.com

#### 5. Clone Your Forked Repository  
Clone your forked repo to your local machine:
```bash
git clone https://github.com/YOUR_USERNAME/rest-api-tests-python.git
```

#### 6. Open the Project in VS Code  
Navigate to the cloned folder and open it in VS Code.

---

### Docker & Jenkins Setup

#### 7. Install Docker Desktop  
Download from:  
👉 https://www.docker.com/products/docker-desktop

After installation, verify:
```bash
docker -v
```
You should see the installed Docker version.

#### 8. Pull the Jenkins Docker Image  
Run the following command in the terminal:
```bash
docker pull jenkins/jenkins:lts
```

---

### ✅ You're All Set!

Make sure everything is installed and working **before the workshop** to ensure smooth participation.  
See you soon!

