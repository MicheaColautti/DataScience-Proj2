# Data Science Project 2
### Bike analysis


- **Michea Colautti**  
- **Julian Cummaudo**  
- **Andrea Masciocchi**



## 📊 Project Overview
# Motorcycle Specs Analysis

In this project, we analyze a real-world dataset of motorcycle specifications drawn from online listings. Our objective is to uncover meaningful patterns and correlations—such as how engine displacement relates to weight, or which categories tend to offer the highest ground clearance—that can help enthusiasts, retailers, and engineers alike better understand the market and performance characteristics across different models.

The dataset includes features such as:

- **Model**, **Year**, **Category**  
- **Displacement**, **Engine type**, **Torque**, **Bore × Stroke**  
- **Fuel system**, **Fuel control (valve train)**, **Cooling system**  
- **Gearbox**, **Final drive**, **Frame type**  
- **Rake (fork angle)**, **Trail**, **Front & Rear suspension** travel  
- **Tyre sizes**, **Front & Rear brakes** (disc diameter & caliper type)  
- **Seat height**, **Ground clearance**, **Wheelbase**, **Fuel capacity**  
- **Color options**, **Starter type**  
- **Metadata** (user rating placeholder, comments, finance/insurance links, related-bikes references)


## 📁 Deliverables


- 📽 **Presentation Slides** (PDF or PowerPoint)  
  A concise, visual summary of our findings—designed to be presented in **under 7 minutes**. We’ll highlight key distributions, standout models, and practical recommendations.

- 📓 **Jupyter Notebook** (.ipynb and .html)  
  The notebook includes:  
  - Dataset source & structure (JSON ➔ normalized tables)  
  - Data-cleaning & unit-parsing steps (e.g. extracting numeric values for displacement, torque, dimensions)  
  - Well-commented code & explanatory markdown cells  
  - Charts & visualizations (histograms, scatter plots, boxplots) for exploratory analysis  



## 🔎 Dataset Summary

- **Name**: Motorcycle Specifications  
- **Format**: JSON (one record per model, indexed by ID)  
- **Key Attributes**:  
  - **Identification**: Model, Year, Category  
  - **Technical**: Displacement (cc), Engine type, Torque (Nm), Bore × Stroke (mm)  
  - **Chassis & Suspension**: Frame material, rake/trail, suspension travel  
  - **Dimensions**: Seat height, ground clearance, wheelbase  
  - **Wheels & Brakes**: Tyre sizes, disc diameter, caliper specs  
  - **Capacity & Options**: Fuel capacity (L), color variants, starter method  
- **Why it’s interesting**:  
  This dataset aggregates a broad variety of off-road, sport, touring, and commuter bikes with detailed spec sheets—offering insight into design trade-offs (power vs. weight, comfort vs. agility), category trends, and outlier models.


