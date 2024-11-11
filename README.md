# BalanceIQ
<p>BalanceIQ is a financial data processing and analytics platform designed to help businesses and individuals gain insights into their financial performance. The platform allows users to upload financial data, generate detailed reports, and visualize their profit/loss through interactive line graphs. With BalanceIQ, users can easily track their income, expenses, and profitability, and make informed financial decisions.</p>

## :sparkles: Features


<li>📜 File Upload: Upload CSV files with financial data , including revenue, expenses and Net income.</li>
<li>:mag: Data Analysis: Automatically calculates profit and loss, p[rofit margin and  Growth Rate.</li>
<li>📊 Profit/Loss Reports: Generat detailed financial reports for different periods.</li>
<li>📈 Visual Graphs: View interactive graphs that show profit/loss trends over time.</li>
<li>👥 User Management: User Authentication and secure login systems for lets say companies or private entities that are using the platform.</li>

## 💻 Installation
**🧪 Prerequisites**
<p>To get started with BalanceIQ, you will need o have the following installed on your system:</p>
<li>Python version 3.8</li>
<li>pip(Python Packages Installer</li>
<li>A Virtual Environment</li>
<li>Flask framework</li>
<li>MySQL server for our database</li>

## 🔧 Step-By-Step setup
<li>Clone the repository:</li>

```bash
git clone https://github.com/yourusername/balanceiq.git
cd balanceiq
```
<br>

<li>Create a virtual environment:</li>

```bash
python -m venv venv
```
<br>
<li>Activate the virtual environment:</li>

<p>On Windows:</p>

```bash
venv\Scripts\activate
```
<br>
<p>On Mac/Linux:</p>

```bash
source venv/bin/activate
```
<br>
<li>Install the required dependencies:</li>

```bash
pip install -r requirements.txt
```
<br>
<p>This will install Flask and other necessary libraries like Flask-SQLAlchemy for database interactions, Chart.js (via JavaScript in the frontend), and any other dependencies specified in the requirements.txt file.</p><br>

<li>Set up the database:</li>

```bash
python run.py
```
This will create the necessary tables and set up the database for the application.

<li>Run the application:</li>

To start the server and run the app locally, use:

```bash
python run.py
```
<br>
<p>The app will be available at http://127.0.0.1:5000/ by default.</p>
