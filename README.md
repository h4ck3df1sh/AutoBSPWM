## AutoBSPWM - A Customization Guide

Maximize your Ubuntu 22.04 or Kali Linux efficiency with this streamlined setup. It's designed to quickly tailor your system for enhanced productivity.

### Quick Start

Automate your system's transformation with our scripts, ensuring a productive environment from the get-go.

### Steps

- **Prepare Your System:**
  - Update and install essentials:
    ```bash
    sudo apt update && sudo apt full-upgrade -y
    sudo apt install ansible-core git -y
    ```
  - Clone the setup repository:
    ```bash
    mkdir Github && cd Github
    git clone https://github.com/h4ck3df1sh/AutoBSPWM.git && cd AutoBSPWM
    ```

- **Authenticate:**
  - Cache sudo for seamless setup:
    ```bash
    sudo whoami
    ```

- **Install:**
  - Deploy configurations with Ansible:
    ```bash
    ansible-playbook main.yml
    ```

- **Switch Environment:**
  - Post-install, choose 'bspwm' at the login screen.

- **Enjoy:**
  - Log back in to experience your tailored workspace.

**Note:** Compatible with both Ubuntu 22.04 and Kali Linux, though minor adjustments may be needed for Kali.