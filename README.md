# docker-setup-ubuntu Ubuntu 20.04.6 LTS
docker-setup-ubuntu

## Setting Up Docker on Ubuntu 20.04.6 LTS

To streamline the Docker installation process, I've included a script in this repository. Follow the steps below to download and execute the script on your local machine with administrative permissions.

### Steps:

1. **Download the Script**:
   - Locate and download the `docker-setup.sh` file from this repository to your local computer.

2. **Open Terminal**:
   - Launch the terminal on your Ubuntu system and verify the current version.
   - 
		# Verifiy the server version
		$ lsb_release -a
		No LSB modules are available.
		Distributor ID:	Ubuntu
		Description:	Ubuntu 20.04.6 LTS
		Release:	20.04
		Codename:	focal

 
3. **Navigate to the Download Directory**:
   - By default, downloaded files are saved in the `Downloads` folder. You can navigate to this directory using the command:
     ```bash
     cd ~/Downloads
     ```

4. **Run the Script with Administrator Permissions**:
   - Execute the script with the following command:
     ```bash
     sudo sh ./docker-setup.sh
     ```

   - **Example**:
     ```bash
     sudo sh /home/user/Downloads/docker-setup.sh
     ```

### Important Note:
- **File Path**: Ensure that you check the file path where the script is downloaded. The default location is usually the `Downloads` folder.
 
