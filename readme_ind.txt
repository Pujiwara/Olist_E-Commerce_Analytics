Judul Project:
Olist E-Commerce Analytisis

Deskripsi:
Project ini merupakan analisis menyeluruh terhadap dataset Olist—salah satu marketplace terbesar di Brasil.Dataset mencakup orders, customers, sellers, products, payments, dan reviews.
Tujuan utama project ini adalah membangun end-to-end analytics pipeline mulai dari pembuatan data warehouse PostgreSQL, transformasi ETL, hingga Power BI dashboard sebagai media eksplorasi insight bisnis.

Tools:
PostgreSQL, PowerBI

Insight:
1. GMV Tumbuh Stabil. Total GMV menunjukkan tren kenaikan yang konsisten dari waktu ke waktu
2. Category Beleza & Saúde menjadi Growth Driver Utama dengan GMV tertinggi dan jumlah order terbanyak. AOV category ini sebesar 163, sedikit di atas AOV total (159), menunjukkan kategori ini tidak hanya besar secara volume tetapi juga menguntungkan.
3. Marketplace tidak bergantung pada Big Seller. Dengan  total sellers 3095 , top 10 sellers menyumbang sekitar 14% GMV. Ini berarti resiko ketergantungan rendah. Pasar bersifat kompetitif dengan kontribusi menyebar.
4. Delivery Performance bervariasi antar State.Di beberapa daerah performance delivery days lebih dari 23 hari, yaitu: PA, AL, AM, AP, RR. Hal ini menandakan tantangan logistik di daerah tertentu dengan akses geografis sulit.
5. Operasional logistik sangat efsien, karena delivery success rate (97,02%) dan On-Time Delivery (96,30%) sangat tinggi.
6. Berdasarkan RFM Quadrant, mayoritas customer berada di cluster Potensial dan Loyal, dibandingkan Champions yang berjumlah jauh lebih kecil. Ini membuka peluang untuk fokus retensi dapat diarahkan untuk mengonversi pelanggan Potensial & Loyal menjadi Champions melalui loyalty program, bundling, personalized campaign, atau push notification berbasis behavior
7. Average review Score tinggi, menunjukkan customer puas. Namun terdapat 15% negative review rate, dengan rating 1 mencapai 11K dari total 99K reviews

Dataset:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Project ini membangun Star Schema yang terdiri dari:
fact_orders
fact_order_items
fact_payments
fact_reviews
dim_customers
dim_sellers
dim_products
dim_dates
dim_geolocation (optional)
rfm_segment

Proses ETL dilakukan melalui SQL di PostgreSQL dengan berbagai langkah:
- Standardisasi format tanggal
- Merging dan cleaning data per table- 
- Key mapping antara fact & dimension
- Penambahan calculated attributes

Selanjutnya PowerBI import data tersebut untuk dibuat dashboard dengan struktur:
- Summary Overview
- Category Performance
- Seller Performance
- Customer & Delivery Performance
- Review & Insight