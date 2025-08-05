Metal HMI (Java Swing + MySQL Application)

This is a desktop application built using "Java Swing" and "MySQL", designed for managing and tracking slab data in a metal manufacturing environment. 
It allows users to "create", "read", "update" and "delete" records across two tables: "METAL_MASTER" and "METAL_DETAILS".

---

📦 Features

- CREATE ENTRIES  
  Input slab details and chemical quantities using a GUI form.

- READ ENTRIES  
  Filter slab data by shift or steel grade and view detailed chemical composition.

- UPDATE ENTRIES  
  Modify existing slab records in both `METAL_MASTER` and `METAL_DETAILS`.

- DELETE ENTRIES  
  Remove slab records by SLAB_NO along with linked chemical data.

---

🧮 Database Overview

The application uses a MySQL database named "METAL_DB", which contains two primary tables:

- METAL_MASTER – Stores core slab metadata like SLAB_NO, HEAT_NO, STEEL_GRADE, SHIFT, etc.
- METAL_DETAILS – Stores chemical element quantities for each slab (e.g., Al, B, Ga, In, Tl).

All slabs are uniquely identified by "SLAB_NO", which serves as a foreign key in the "METAL_DETAILS" table.

---

⚙️ Technologies Used

- Java (Swing GUI)
- MySQL (via JDBC)
- Eclipse IDE
- SQL



