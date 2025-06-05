# Daikibo Telemetry Analysis Task

Your task is to **analyze the telemetry data collected by Daikibo** using a software called **Tableau**. Follow the steps below carefully:

---

## 🛠️ Step-by-Step Instructions

1. **Download & Install Tableau**  
   - Grab the **free trial** of Tableau from the link provided in the **Resources** section.  
   - Install it on your system and **register using the same email** you used for the download.

2. **Import the Data**
   - Download `daikibo-telemetry-data.json.zip` from the resources.
   - **Unzip** the file.
   - Open Tableau and **import** the unzipped `.json` file.

3. **Create a Calculated Field**
   - Create a new **calculated measure field** called `Unhealthy`.
   - Set its value to `10` for every "unhealthy" status, representing **10 minutes of potential downtime** since the last message.

4. **Visualizations**
   - Create a **bar chart** named **"Down Time per Factory"**.
   - Create a second sheet with a bar chart named **"Down Time per Device Type"**.

5. **Build a Dashboard**
   - Combine the two charts into a **single dashboard**.
   - Set the **first chart ("Down Time per Factory") as a filter**, so that selecting a factory updates the second chart to show downtime by device type *within that factory*.

6. **Capture & Submit**
   - Click the bar for the **factory with the most downtime**.
   - Take a **screenshot** of your dashboard with the selected filter.
   - **Upload** the screenshot as your task submission.

---

## 📁 Resources
- 📎 Tableau Free Trial Download  
- 📎 `daikibo-telemetry-data.json.zip`  
- 📎 Task Guide (PDF)
