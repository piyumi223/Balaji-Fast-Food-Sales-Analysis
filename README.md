# 🍔 Balaji Fast Food Sales Analysis

An Excel-based sales analytics dashboard for **Balaji Fast Food**, covering 1,000 transactions from April 2022 to March 2023. The workbook includes raw data, pivot table analyses, and an interactive dashboard with slicers.

---

## 📊 Dashboard Preview
<img width="823" height="622" alt="image" src="https://github.com/user-attachments/assets/c6c65fc7-0fed-4edd-a37f-f6b4b0fa0556" />



---

## 📁 Dataset

| Field | Description |
|-------|-------------|
| `order_id` | Unique order identifier |
| `date` | Transaction date (Apr 2022 – Mar 2023) |
| `item_name` | Product name (Aalopuri, Cold coffee, Frankie, Panipuri, Sandwich, Sugarcane juice, Vadapav) |
| `item_type` | Category — Fastfood or Beverages |
| `item_price` | Unit price (₹) |
| `quantity` | Items per order |
| `transaction_amount` | Total order value (₹) |
| `transaction_type` | Payment method — Cash, Online, or Unknown |
| `received_by` | Server gender — Mr. or Mrs. |
| `time_of_sale` | Time of day — Morning, Afternoon, Evening, Night, Midnight |

- **Records:** 1,000 orders
- **Period:** April 2022 – March 2023
- **Total Revenue:** ₹275,230

---

## 🔍 Analyses

The workbook contains the following analysis sheets, each feeding into the dashboard:

| Sheet | Analysis | Key Insight |
|-------|----------|-------------|
| `sales_trend` | Monthly revenue by item type | Fastfood drives ~69% of revenue vs ~31% for Beverages |
| `total_rev` | Total revenue per item | Sandwich (₹65,820) and Frankie (₹57,500) are the top earners |
| `best_selling_by_qty` | Items sold by quantity | Cold coffee leads with 1,361 units, followed by Sugarcane juice (1,278) |
| `avg_transaction_monthly` | Avg transaction value by item per month | Sandwich averages the highest transaction value, peaking at ₹625.71 in December |
| `avg_basket_size` | Average basket size per item | Overall average is ~8.2 items per order; Sandwich has the highest avg order value (₹510) |
| `peak_selling_hours` | Revenue & order distribution by time of day | Night (22.6%) and Afternoon (20.5%) generate the most revenue |
| `cash vs online sales` | Payment method breakdown | Cash (47.6%) edges out Online (41.7%); 10.7% are Unknown |
| `online vs Cash transaction trend` | Monthly payment method trend | Cash and Online fluctuate month to month |Online transactions peaks during festive seasons in India|
| `server_type_sales_dif` | Revenue by server gender across time of day | Male servers (Mr.) generate higher revenue in most time slots |
|Female Servers generate high sales during midnight|
| `Sales_time` | Item-level sales by time of day | Detailed breakdown of each item's performance across time periods |

---

## 📈 Dashboard Features

The interactive **Dashboard** sheet includes:

- **4 KPI cards** — Total Revenue, Avg Monthly Revenue, Avg Basket Size, Peak Selling Hours
- **Revenue Trend** — Monthly revenue split by Fastfood vs Beverages
- **Total Sales Per Item** — Bar chart of revenue by product
- **Total Number of Items Sold** — Bar chart of quantity by product
- **Avg Transaction Value by Item (Monthly)** — Line chart tracking monthly trends per item
- **Item Sales by Time of Day** — Clustered column chart
- **Cash vs Online** — Pie chart + line trend
- **Server Type Sales Difference** — Revenue comparison by server gender
- **Interactive Slicers** — Filter by Date, Item Name, and Item Type

---

## 🛠️ Tools Used

- Microsoft Excel (pivot tables, charts, slicers)
- Data cleaning and analysis done within the workbook

---

## 📂 File Structure
├── fast_food_dataset.xlsx │ ├── Data # Raw transaction data (1,000 rows) │ ├── sales_trend # Pivot: monthly revenue by item type │ ├── total_rev # Pivot: total revenue per item │ ├── best_selling_by_qty # Pivot: quantity sold per item │ ├── avg_transaction_monthly # Pivot: avg transaction value by item/month │ ├── avg_basket_size # Pivot: avg basket size per item │ ├── peak_selling_hours # Pivot: time-of-day distribution │ ├── cash vs online sales # Pivot: payment method breakdown │ ├── online vs Cash transaction... # Pivot: monthly payment method trend │ ├── server_type_sales_dif # Pivot: revenue by server gender │ ├── Sales_time # Pivot: item sales by time of day │ └── Dashboard # Interactive dashboard with charts & slicers └── README.md

--- ## 📝 License This dataset is used for educational and analytical purposes.
