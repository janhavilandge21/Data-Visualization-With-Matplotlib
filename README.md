#📊 Data Visualization with Matplotlib 

Data Visualization with Matplotlib This project demonstrates various data visualization techniques using Matplotlib in Python. It focuses on exploring and analyzing a dataset containing monthly sales and profit values. A simple interactive GUI is also created using Gradio to allow users to select and view different types of plots.

🧠 Key Concepts Covered
 Line Plot

Bar Chart

Pie Chart

Scatter Plot

Histogram

Box Plot

Interactive Visualization using Gradio

📁 Dataset
python
Copy
Edit
data = {
    "Month": ["Jan", "Feb", "Mar", "Apr", "May", "Jun"],
    "Sales": [10000, 12000, 15000, 13000, 17000, 16000],
    "Profit": [2000, 3000, 4000, 2500, 3500, 3000]
}
📌 Visualizations
📈 Line Plot – Shows the sales trend over months

📊 Bar Chart – Compares sales and profit

🥧 Pie Chart – Displays profit distribution

⚪ Scatter Plot – Analyzes correlation between sales and profit

🧮 Histogram – Shows distribution of sales

📦 Box Plot – Displays spread and outliers of profit

🧪 Tools Used
Python

Matplotlib

Pandas

Gradio (for GUI)

🚀 How to Run
bash
Copy
Edit
pip install matplotlib pandas gradio
python your_script_name.py
The Gradio interface will launch locally at:
http://127.0.0.1:7861/

📸 Demo
Choose plot type (Line, Pie, Bar, etc.) in Gradio to view visualization interactively.

📄 Output Sample
Sales vs Profit Graph

Monthly Profit Pie Chart

Histogram of Sales Data

Profit Box Plot
