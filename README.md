💄 BeautyCommerceOS
Enterprise-Scale Synthetic Beauty Ecommerce Warehouse

A high-fidelity synthetic data warehouse simulating the complete operational stack of a global beauty & cosmetics ecommerce company.

Built for:

🤖 Autonomous analyst benchmarking
📊 BI & analytics engineering
🧠 Agentic AI systems
🏗️ Data warehouse testing
🔍 Causal inference & root-cause analysis
📈 Attribution & experimentation modeling

Inspired by real-world enterprise commerce systems — but fully synthetic, open, and research-friendly.

🌍 What is this?

BeautyCommerceOS is not a toy ecommerce dataset.

It is a fully simulated enterprise operating system containing:

clickstream events
identity stitching
orders & payments
inventory & fulfillment
attribution systems
influencer commerce
experimentation infrastructure
finance & accounting layers
KPI semantic conflicts

This dataset was designed to emulate the analytical complexity of modern commerce organizations.

🧱 Warehouse Architecture
warehouse/
├── bronze/
│   ├── sessions.parquet
│   ├── events.parquet
│   └── anonymous_users.parquet
│
├── silver/
│   ├── products.parquet
│   ├── skus.parquet
│   ├── brands.parquet
│   ├── suppliers.parquet
│   ├── warehouses.parquet
│   └── identity_map.parquet
│
├── gold/
│   ├── orders.parquet
│   ├── order_items.parquet
│   ├── carts.parquet
│   ├── payments.parquet
│   ├── refunds.parquet
│   ├── campaigns.parquet
│   ├── attribution.parquet
│   ├── inventory_snapshots.parquet
│   ├── shipments.parquet
│   ├── invoices.parquet
│   ├── pnl_daily.parquet
│   └── ...
🧠 What Makes This Different?

Most ecommerce datasets only contain:

orders
products
customers

BeautyCommerceOS models the entire enterprise.

Including:

📱 Behavioral Analytics
sessions
clickstream events
funnel progression
add-to-cart flows
attribution leakage
🛒 Commerce Operations
carts
orders
order items
payments
refunds
subscription behavior
🚚 Supply Chain & Logistics
inventory snapshots
warehouse transfers
stockouts
supplier delays
shipments
delivery failures
📣 Marketing & Attribution
campaigns
ad impressions
ad clicks
influencer commerce
multi-touch attribution
ROAS distortion
🧪 Experimentation
A/B testing
treatment/control groups
traffic allocation
experiment contamination
💰 Finance & Accounting
invoices
journal entries
revenue recognition
P&L reporting
KPI definition conflicts
⚠️ Intentional Realism

This warehouse intentionally includes:

attribution ambiguity
operational inconsistencies
delayed reconciliation
refund lag
coupon abuse
stockouts
payment retries
KPI disagreements
semantic conflicts

Because:

real enterprise data is messy

The goal is to benchmark systems against reality — not clean textbook tables.

📦 Dataset Characteristics
Attribute	Value
Domain	Beauty & Cosmetics Ecommerce
Format	Parquet
Total Size	< 10 GB
Geography	US, UK, DE, FR, CA
Time Coverage	~2 years
Data Type	Fully synthetic
Warehouse Style	Bronze / Silver / Gold
Granularity	Event-level
Identity Model	Anonymous + stitched users
🔍 Example Questions You Can Ask
📈 Marketing
Why did TikTok ROAS improve while profit declined?
Which influencers drive low-retention customers?
🚚 Supply Chain
Which stockouts caused the highest revenue loss?
Which warehouses generate the most delayed deliveries?
💰 Finance
Why does finance revenue differ from marketing revenue?
How much revenue was recognized late?
🧠 Autonomous Analyst Benchmarks
Root cause analysis
Causal reasoning
Cross-functional diagnosis
Metric reconciliation
Semantic consistency checks
🛠️ Recommended Stack
Warehouses & Query Engines
DuckDB
Apache Spark
Snowflake
Google BigQuery
Python Libraries
Polars
Pandas
DuckDB Python Client
PyArrow
🚀 Suggested Use Cases

✅ Autonomous AI agents
✅ Analytics engineering
✅ Synthetic enterprise benchmarking
✅ Data quality tooling
✅ BI dashboards
✅ Attribution modeling
✅ Supply chain analytics
✅ Experimentation systems
✅ LLM evaluation frameworks
✅ Semantic layer testing

🔒 Data Safety

This dataset is:

✅ Fully synthetic
✅ Generated programmatically
✅ Contains no PII
✅ Contains no real customers
✅ Contains no payment data
✅ Contains no proprietary enterprise records

📜 License

Recommended:

CC BY 4.0

Use freely for:

research
benchmarking
education
experimentation
open-source tooling
🤝 Contributions

PRs are welcome for:

new anomaly generators
causal benchmark suites
warehouse extensions
dbt models
semantic layers
synthetic CRM systems
forecasting pipelines
observability tooling
🧩 Future Extensions

Potential future modules:

customer support systems
CRM lifecycle automation
loyalty programs
subscription commerce
feature stores
retail/POS systems
forecasting infrastructure
fraud systems
schema drift simulation
🏁 Final Goal

BeautyCommerceOS was designed to answer one question:

Can autonomous systems reason across the complexity of a real enterprise?

Not just dashboards.
Not just SQL.
But causality, inconsistency, ambiguity, and operational reality.
