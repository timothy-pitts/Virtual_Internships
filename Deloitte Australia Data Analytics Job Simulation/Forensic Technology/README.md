## 🧩 Forensic Technology Assignment

⚠️ After a worrisome number of internal complaints about **gender inequality in salaries**, **Daikibo Industrials** decided to launch an internal investigation.  

🧠 The **Forensic Tech team** built an algorithm to quantify the **“level of gender pay equality”** across job roles and locations. The **Forensics Lead** suggested that I take the lead on completing this part of the project.  

📊 The team processed all data on employee compensation and generated an Excel file. The file includes three columns:  
- 🏭 **Factory**  
- 👔 **Job Role**  
- ⚖️ **Equality Score** *(integer, ranging from -100 to +100; 0 is ideal)*  

🎯 My task was to create a **4th column** called **“Equality Class”**, classifying equality scores into three categories:  
- ✅ **Fair** → ±10  
- ⚠️ **Unfair** → < -10 **and** > 10  
- 🚨 **Highly Discriminative** → < -20 **and** > 20

While I could have typed each individual cell, I decided to instead use a function to speed up the process, dragging the function into each cell in the fourth column:

=IFS(C2 < -20, "Highly Discriminative", C2<=-10, "Unfair",C2<=10, "Fair", C2 >10, "Unfair", C2>20, "Highly Discriminative")

📸 The following image shows the **final results** of my data analysis & showed which job roles had fair, unfair, or discriminitive conditions.

<img width="606" height="398" alt="image" src="https://github.com/user-attachments/assets/49b8c574-4763-4d84-82f0-0460a0f294d4" />

