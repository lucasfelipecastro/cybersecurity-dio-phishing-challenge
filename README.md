# Disclaimer

This project is for **educational purposes only**. It aims to demonstrate how social engineering techniques are used to capture login credentials, with the goal of raising **awareness about cybersecurity threats**. None of the steps described here should be performed outside of controlled testing environments or without **explicit consent** from all parties involved.

---

# Objective

The goal is to simulate a fake login page using a virtual machine running Kali Linux and the Social-Engineer Toolkit (SEToolkit). This simulation is intended for **learning and ethical hacking training** purposes, helping students understand how phishing attacks operate in order to defend against them.

---

# Tools Used

- **Operating System:** Kali Linux on Oracle Virtual Box
- **Tool:** SEToolkit (Social-Engineer Toolkit)  
- **Networking:** Local network interface (using `ifconfig` to obtain IP)

---

# Procedure Overview

1. **Gain root access:**  
   Start a terminal session as the root user:
   ```bash
   sudo su
2. **Launch the SEToolkit:**
   Execute the toolkit with:
   ```bash
   setoolkit
3. **Choose attack type:**
   - Select: Social-Engineering Attacks
4. **Select attack vector:**
   - Choose: Website Attack Vectors
5. **Select method:**
   - Choose: Credential Harvester Attack Method
6. **Clone a legitimate site:**
   - Choose: Sitet Cloner
   - Enter the target URL (for visual replication only):
       ```bash
       http://www.facebook.com
7. **Identify the machine's IP address:**
Use the command below to find the local IP address, which will be needed to access the cloned site from a browser:
    ```bash
    ifconfig

# Notes
- This simulation was conducted entirely within a virtualized Kali Linux environment.
- No real credentials were collected or exposed.
- The purpose of this documentation is strictly for ethical hacking education and cybersecurity training.
