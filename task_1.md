## Software Installation

### Prerequisites
Install Zadig from [here](https://zadig.akeo.ie/)

### Installation Steps

1. **Install Zadig**
   - Download and install Zadig from the [official website](https://zadig.akeo.ie/)

2. **Configure Zadig**
   - Follow the steps shown in the image below:
   
   ![Zadig Configuration](https://github.com/user-attachments/assets/47c750f4-f71b-40e0-975d-4918815e5b26)

3. **Download and Extract Freedom Studio**
   - Download Freedom Studio from [this link](https://vsd-labs.sgp1.cdn.digitaloceanspaces.com/vsd-labs/VSDSquadronPRO.tar.gz)
   - Extract the downloaded file to your desired location

4. **Launch Freedom Studio**
   - Navigate to the extracted folder and open `FreedomStudio-3-1-1`
   - Click **Run Anyway** to launch the IDE
   
   ![Freedom Studio Launch](https://github.com/user-attachments/assets/eb4b8237-7343-4f92-898a-5ee978053f9f)
   
   ---

## Creating Your First Project

Follow these steps to create and run a validation project:

### Step 1: Create a Validation Project
- Open Freedom Studio and select the option to create a new Validation project
  
  ![Create Validation Project](https://github.com/user-attachments/assets/bf916718-a4ef-420d-b149-1e2e27f2d06f)

### Step 2: Configure Project Settings
- Change the target settings as needed and click **Finish** to complete project setup
  
  ![Configure Target](https://github.com/user-attachments/assets/0bf03ee8-9b96-49bf-ae90-54219bd628f4)

### Step 3: Connect Board and Debug
- Connect your VSDSquadronPRO board to your computer
- Select **OpenOCD** as the debugging tool
- Click the **Debug** button to start debugging
  
  ![Debug Configuration](https://github.com/user-attachments/assets/994688e4-8fc8-4d3a-bcbb-6505971ce545)

---

## Verification

After clicking the **Debug** button, follow these steps:

1. Click the **Run** button to execute your program
2. Observe the terminal output in Freedom Studio
3. Observe the LED behavior on the VSDSquadronPRO board

If your output matches the image below, the installation and setup have been completed successfully.

![Successful Output](https://github.com/user-attachments/assets/82fa26cb-2c67-4c6a-8ac9-9ac243ea02f1)