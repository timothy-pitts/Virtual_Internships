## 🧩 Job Simulation: Tableau Telemetry Data Analysis

As part of this **Deloitte Australia Data Analytics Job Simulation**, my task was to **analyze the telemetry data** collected by **Daikibo** using **Tableau**.  

### 🧠 Here’s how I approached the project:  
- **Imported the dataset** by downloading the `daikibo-telemetry-data.json.zip` file, unzipping it, and loading it into Tableau.  
- **Created a calculated field** called `"Unhealthy"` with a value of **10** for every unhealthy machine status — representing **10 minutes of potential downtime** since the previous message.  
- **Built a bar chart** titled **“Down Time per Factory”** 📊 to visualize total downtime across all factory sites.  
- **Created another sheet** with a bar chart titled **“Down Time per Device Type”** ⚙️ to explore which machine types were most affected.  
- **Designed a Tableau Dashboard** 💠 combining both charts and set the first chart as an **interactive filter** — selecting a factory in Chart 1 dynamically filtered downtime by device type in Chart 2.  
- Finally, I **selected the factory with the highest downtime**, took a **screenshot** 📸 of the completed dashboard, and **uploaded it** as the submission for this simulation task.

<img width="966" height="940" alt="image" src="https://github.com/user-attachments/assets/8143888c-044f-4c5e-8c22-dd2fa4e3c5b5" />
