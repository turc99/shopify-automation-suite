# Shopify Automation Suite

A fully automated Shopify logistics pipeline that processed orders, forwarded them to a warehouse, and fulfilled deliveries without the need for manual stock handling.

## 🔥 Features
- Auto-import new products
- Auto-forward customer orders to warehouse API
- Auto-generate tracking numbers and fulfil orders
- Scheduled analytics + profit reports
- Inventory sync between supplier → store
- Fully “hands-off” fulfilment pipeline

## 🧠 Tech Stack
- Python 3
- Shopify Admin API
- Requests + Pandas
- Cron / schedulers
- Logging system

---

## 📦 Architecture Overview
- Orders are fetched via Shopify API  
- Validated + formatted  
- Forwarded to warehouse endpoint  
- Warehouse ships directly to customer  
- Tracking info is pushed back to Shopify  
- Status updates → customer notified  

---

## 🚀 How to Use
1. Add your API keys to `.env`
2. Run `python auto_fulfill.py`
3. Run `python sync_inventory.py`
4. (Optional) Set up cron jobs for automation

---
