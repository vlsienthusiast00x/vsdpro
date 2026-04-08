# Hardware Setup & Validation

## Software Installation

1. **Install Zadig**  
   Download and install Zadig from the official site: [https://zadig.akeo.ie/](https://zadig.akeo.ie/).  
   After installation, follow the steps shown below:  
   ![Zadig Setup](https://github.com/user-attachments/assets/47c750f4-f71b-40e0-975d-4918815e5b26)

2. **Download Freedom Studio**  
   Download Freedom Studio from the following link:  
   [VSDSquadronPRO.tar.gz](https://vsd-labs.sgp1.cdn.digitaloceanspaces.com/vsd-labs/VSDSquadronPRO.tar.gz)  

   Extract the downloaded file. Inside the extracted folder, locate **FreedomStudio-3-1-1** and launch it.  
   If prompted with a security warning, select **Run Anyway**.  
   ![Freedom Studio Launch](https://github.com/user-attachments/assets/eb4b8237-7343-4f92-898a-5ee978053f9f)

---

## Example Software Project

1. **Create a Validation Project**  
   Open Freedom Studio and create a new validation project.  
   ![Validation Project](https://github.com/user-attachments/assets/bf916718-a4ef-420d-b149-1e2e27f2d06f)

2. **Configure Target**  
   Select the appropriate target configuration and click **Finish**.  
   ![Target Configuration](https://github.com/user-attachments/assets/0bf03ee8-9b96-49bf-ae90-54219bd628f4)

3. **Connect and Debug**  
   - Connect the **VSDSquadronPRO** board.  
   - Open **OpenOCD**.  
   - Click **Debug** to start the session.  
   ![OpenOCD Debug](https://github.com/user-attachments/assets/994688e4-8fc8-4d3a-bcbb-6505971ce545)

---

## Final Output Verification

After starting the debug session:  
- Click **Run**.  
- Observe the terminal output and the LED on the board.  

If the output matches the screenshots below, the installation and setup of Freedom Studio has been successfully completed.  

![Final Output](https://github.com/user-attachments/assets/82fa26cb-2c67-4c6a-8ac9-9ac243ea02f1)

---

✅ **You are now ready to proceed with hardware validation using Freedom Studio and the VSDSquadronPRO board.**
