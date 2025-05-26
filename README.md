# Real-Time Retail Stream Simulation with PostgreSQL

This project simulates a real-time stream of retail transactions using Python and continuously inserts the data into a cloud-hosted PostgreSQL database on AWS RDS. It then visualizes product revenue in real time using Matplotlib.

## Tools Used
- **Python (Pandas, SQLAlchemy)** for data generation, database interaction, and visualization
- **AWS RDS (PostgreSQL)** for cloud-hosted relational data storage
- **Matplotlib** for revenue visualization

## What This Project Does
1. Randomly generates 20 individual retail transactions (product, quantity, price, timestamp)
2. Inserts one transaction every 2 seconds into an AWS RDS PostgreSQL table
3. Visualizes total revenue by product in a clean bar chart with dollar amounts

## How to Run This Yourself
1. Clone this repo or open the notebook in Google Colab
2. Replace the `host`, `username`, and `password` placeholders with your credentials
3. Run all cells to simulate data streaming and database insertion

## Sample Output
- Live retail transactions inserted into `retail_stream` table
- Visual chart showing top-performing products by revenue

## Skills Demonstrated
- Real-time data simulation
- PostgreSQL integration
- Secure credential handling
- Dynamic data visualization
