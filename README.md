# process-optimization

# Manufacturing Scheduling Optimization System

A web-based optimization platform for a manufacturing company scenario where 100 staff operate multiple machines with different skill strengths. The system uses Google O-R Tools and Odoo Platform to optimize assignments, minimize production costs, and meet human-resource constraints.

## 🎯 Problem Summary
- 100 staff with different machine skill strengths  
- Machines require skilled operators  
- Max 5 working days/week per staff  
- Mandatory 2 rest days  
- Training pathways for staff to learn new machines  
- Product deadlines must be met  
- Goal: optimize schedules, reduce time and cost


## 💡 Features
- Constraint-based scheduling using OR-Tools  
- Staff-machine compatibility matrix  
- Automatic assignment generator  
- Gantt chart visualization (frontend)  
- REST API for solving optimization models  

## ⚙️ Tech Stack
- Odoo For Business
- Angular  
- NestJS (or Flask, depending on version)  
- Google OR-Tools (CP-SAT)  
- MySQL + MikroORM  
- Node.js  
- Docker + GCP Cloud Run (optional)  

## Example Output
Staff schedule (weekly)
Machine utilization chart
Cost minimization results
Training recommendation list
