# 📦 Samsung Supply & Logistics Dashboard — Power BI

> Supply chain and logistics analytics dashboard built in Power BI,
> themed around the Samsung Galaxy S25 Ultra product line.

---

## 📌 Overview

This dashboard provides end-to-end visibility into Samsung's supply chain and logistics operations,
covering supplier performance, inventory control, shipment tracking, cost analysis, and customer demand.
Built entirely in Power BI with custom DAX measures, HTML Content KPI cards, and a clean branded UI.

---

## 📊 Dashboard Pages

| Page | Focus |
|------|-------|
| 🏠 Home | Navigation hub with branded layout |
| 📈 Ejecutivo | Executive KPI summary — revenue, profit, growth |
| 🏭 Supplier | Supplier performance, lead times, defective units |
| 📦 Inventory | Stock levels, safety stock, days of inventory |
| 🚚 Shipment | Delivery tracking, OTD, delay analysis |
| 👤 Customer | Demand patterns and order segmentation |

---

## 📐 DAX Measures

### 💰 Revenue & Profit
| Measure | Description |
|---------|-------------|
| `Gross Revenue` | Total gross income before deductions |
| `Total Revenue` | Consolidated net revenue |
| `Total Profit` | Total profit across all orders |
| `Profit Margin %` | Ratio of profit to total revenue |
| `Growth_revenue` | Revenue growth rate (MoM or YoY) |

### 📦 Inventory
| Measure | Description |
|---------|-------------|
| `Cantidad Inventario` | Current stock quantity |
| `Days_of_Inventore` | Days of inventory remaining |
| `Safty_Stock` | Calculated safety stock level |
| `defective_units` | Total defective units recorded |

### 🚚 Shipment & Orders
| Measure | Description |
|---------|-------------|
| `Envios` | Total shipments count |
| `Total Cantidad Envios` | Total volume dispatched |
| `Total Cantidad Pedido` | Total orders placed |
| `Total Entregados` | Successfully delivered orders |
| `Total Delay Envios` | Shipments delivered late |
| `Perfect Order Rate` | % of orders with no incidents |

### 🏭 Supplier
| Measure | Description |
|---------|-------------|
| `Total Supplier` | Number of active suppliers |
| `avg lead time` | Average supply lead time |
| `Promedio de Plazo de Entrega` | Average delivery time in days |

### 💸 Cost & Discounts
| Measure | Description |
|---------|-------------|
| `Total Unit Cost` | Total unit cost across products |
| `Discount %` | Applied discount percentage |
| `TotaL Discount Order` | Total discounted amount per order |
| `Cantidad Ordenes` | Total number of orders |

---

## 🛠 Tech Stack

| Tool | Usage |
|------|-------|
| Power BI Desktop | Dashboard design and publishing |
| DAX | All calculated measures and KPIs |
| SQL Server | Data source and transformations |
| Python | ETL pipeline and data generation |
| HTML Content (DAX) | Custom styled KPI cards |

---

## 📁 Repository Structure
