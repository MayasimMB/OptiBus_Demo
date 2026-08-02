# 🎥 OptiBus Demonstration

## Watch the Demonstration

If the demonstration video cannot be played directly from GitHub, or if you prefer faster access, you can watch it using the Google Drive link below:

🔗 **Google Drive:**  
https://drive.google.com/file/d/1I_TJyt7b86jYqqwkE_FYDPvklObQ2IeA/view?usp=sharing

---

This folder contains the official demonstration of the OptiBus AI-Based School Bus Routing Optimization System.

The demonstration presents the complete workflow of the system, from uploading student transportation data to generating optimized school bus routes using Student Clustering, Adaptive Large Neighborhood Search (ALNS), and Proximal Policy Optimization (PPO).

## Demonstration Workflow

### Step 1 — Upload Student Transportation Data

The transportation administrator uploads the transportation file containing the students registered for the school transportation service and their geographical locations.

---

### Step 2 — Student Assignment

After importing the transportation data, the system analyzes the geographical locations of the registered students and automatically assigns them to school buses.

---

### Step 3 — Attendance Management

Before the daily trip begins, parents can report their child's attendance status through the parent application.

Students marked as absent are automatically excluded from the transportation plan for that day.

---

### Step 4 — Route Generation

After processing the daily attendance records, the system generates school bus routes based on the students who are attending on that day.

---

### Step 5 — Route Optimization

The generated routes are optimized using the proposed hybrid optimization framework, which combines:

- Student Clustering
- Adaptive Large Neighborhood Search (ALNS)
- Proximal Policy Optimization (PPO)

The optimization process aims to generate efficient school bus routes while satisfying the routing constraints.

---

### Step 6 — Results Visualization

Finally, the optimized transportation plan is presented through the system interfaces.

The parent interface allows parents to review their child's transportation information, while the driver interface displays the assigned route, student list, and trip information for the scheduled journey.
