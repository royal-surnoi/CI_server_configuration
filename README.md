---

# Project Setup Script

This script is designed to configure Jenkins, Git, Maven, Node.js, and Angular on your system. Follow the instructions below to execute the script.

## Prerequisites
- The script requires sudo permissions to execute successfully.
- Ensure that you have the necessary permissions to execute scripts on your system.

## Script Execution

1. Clone the repository to your local machine (if not already done).

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Make sure the script is executable. If it is not, you can change the permissions using:

    ```bash
    chmod +x <script_name>
    ```

3. Execute the script using the `source` command:

    ```bash
    source <script_name>
    ```

    **Note:** It is important to use the `source` command to ensure that any environment variables set by the script are available in your current shell session.

## Script Details

The script will perform the following configurations:

1. **Jenkins**
    - Install Jenkins
    - Configure Jenkins settings

2. **Git**
    - Install Git
    - Configure Git settings (username, email, etc.)

3. **Maven**
    - Install Maven
    - Configure Maven settings

4. **Node.js**
    - Install Node.js
    - Install npm (Node Package Manager)
    - Configure Node.js and npm settings

5. **Angular**
    - Install Angular CLI
    - Verify Angular installation

## Troubleshooting

If you encounter any issues while executing the script, check the following:
- Verify that you have the necessary permissions to install software and modify system settings.
- Check the script for any errors or missing dependencies.

