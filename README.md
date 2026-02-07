# 🐳 Stupid Docker

**Stupid Docker** is a beginner-friendly Bash script that simplifies common Docker commands into an easy-to-use menu interface.

It is designed for:

* Beginners learning Docker
* Users who don’t want to memorize Docker commands
* Quick Docker setup on Linux systems


**Why use Stupid Docker when Docker Desktop already exists?** 
Well, for starters, Docker Desktop is extremely bloated and uses more than the required resources to run. 
Which ultimately drives people to use CLI instead. CLI by default, is a teeny bit complicated for beginners and repetitive even for people who already know what they are doing. 
That is where **Stupid Docker** comes in. **Stupid Docker** can run easily on your 2007 Microwave Potato Computer. 

---

##  Features

* Automatically installs Docker (based on your Linux distro)
* Supports:

  * Debian / Ubuntu
  * RHEL / CentOS / Fedora
  * Arch Linux
  * SUSE
* Simple interactive menu
* Pull images
* Search images
* Run containers
* Stop & start containers
* Remove images & containers
* View Docker help
* No Docker knowledge required

---

##  Requirements

* Linux System (Bare metal, WSL2, Virtual Machines all compatible)
* Bash shell
* Sudo privileges
* Internet connection

---

##  Installation & Usage

### 1️⃣ Clone the repository

```bash
git clone https://github.com/edechime-bryan/stupid-docker
```

### 2️⃣ Move into the project directory

```bash
cd stupid-docker
```

### 3️⃣ Make the script executable

```bash
chmod +x stupid-docker
```

### 4️⃣ Run the script (IMPORTANT)

```bash
./stupid-docker
```

⚠️ **Do NOT run it like this:**

```bash
stupid-docker
```

Linux requires `./` to run scripts in the current directory.

---

##  Why `./` Is Required

For security reasons, Linux does **not** run files from the current directory automatically.

`./` tells the system:

> “Run this file from *this* directory.”

### 5️⃣ If you previously ran this script to install Docker, run it again (./stupid-docker). Ignore this step if Docker was already installed.

```bash
./stupid-docker
```

---

##  Menu Options

| Option | Description             |
| ------ | ----------------------- |
| 1      | Pull Docker image       |
| 2      | Search Docker Hub       |
| 3      | List Docker images      |
| 4      | Run a container         |
| 5      | List running containers |
| 6      | List all containers     |
| 7      | Stop a container        |
| 8      | Start a container       |
| 9      | Remove a container      |
| 10     | Remove an image         |
| 11     | Docker help manual      |
| 12     | Exit                    |

---

##  Supported Linux Distros

* Ubuntu / Debian
* CentOS / RHEL / Fedora
* Arch Linux
* SUSE

---

## ⚠️ Notes

* Script must be run with **sudo privileges**
* Docker will be installed automatically if not found
* Uses official Docker installation methods and scripts from https://docs.docker.com/engine/install/
* Designed for learning and convenience — not to substitute docker (Still uses the docker engine)

---

## 👨‍💻 Author

**Edechime Bryan**
Beginner-friendly Linux & DevOps tooling

---


