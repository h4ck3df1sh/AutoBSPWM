## Personal Ubuntu Customization

Welcome to my customized setup for Ubuntu 22.04, tailored to streamline your workflow and enhance productivity.

### Overview

These scripts automate the customization process for a fresh Ubuntu installation, ensuring that you have all the necessary tools and configurations at your fingertips.

### Installation

Follow these steps to set up your system:

1. **Update Packages:** Begin with a fresh Ubuntu installation and update all packages by running the following commands:

    ```bash
    sudo apt update && sudo apt full-upgrade -y
    sudo apt install ansible-core git -y
    mkdir Tools && cd Tools
    git clone https://github.com/h4ck3df1sh/Ubuntu-BSPWM.git
    ```

2. **Cache Sudo Authentication:** Execute a command with sudo privileges to cache the authentication:

    ```bash
    sudo whoami
    ```

3. **Run Ansible Playbook:** Navigate to the root directory of the repository and run the main playbook:

    ```bash
    cd Ubuntu-BSPWM
    ansible-playbook main.yml
    ```

4. **Select Desktop Environment:** After installation, restart the virtual machine. Before logging in, navigate to the menu in the top-right corner and select 'bspwm'.

5. **Log in and Enjoy:** Log in to your system and experience the enhanced environment tailored to your needs.

**Note:** These Ansible scripts are primarily designed for Ubuntu 22.04 but might be compatible with other Linux distributions like Parrot, Kali and Debian. However, compatibility with these distributions hasn't been thoroughly tested.

### References

Original setup inspired by [iamanetrunner/personal-kali-customization](https://github.com/iamanetrunner/personal-kali-customization). 

For further details and updates, refer to the original repository.
---
