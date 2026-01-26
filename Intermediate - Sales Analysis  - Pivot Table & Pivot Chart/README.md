# 🧩 Mini Project – Excel Intermediate
This folder contains **intermediate-level Excel mini projects** focused on applying analytical functions and structured data analysis techniques to business-oriented datasets. The projects emphasize **data preparation and clear data visualization** using Microsoft Excel.

## 📁 Dataset
- The entire dataset consists of 130 data points. There are 70 original data points and 60 additional data points.
- The dataset covers the period from January 1, 2024 to May 10, 2024.
- A dummy dataset is used for this project.

## 🛠 Tools Used
- Microsoft Excel  
  - Formulas & Functions  
  - Pivot Tables  
  - Pivot Charts   

## 🎯 Project Focus
The Intermediate level projects aim to practice:
- Lookup and logical functions for analysis
- Dynamic formulas and conditional calculations
- Data aggregation using Pivot Tables
- Analytical visualization

## 📘 Key Skills Practiced
- Lookup & Reference: `VLOOKUP` `AND` `IF`
- Dynamic Arrays: `UNIQUE`, `SORT`, `RANDARRAY`
- Conditional Analysis: `COUNTIF`
- Pivot Tables & Pivot Charts

## 🧹 Data Preparation
Common preprocessing steps include:
- Removing duplicate records
- Data Format Normalization
- Handling missing or blank values - (Input Blank values with date before the blank)
- Standardizing text formats and categories - (Using `TRIM` `PROPER` `SUBSTITUTE`)
- Create "Mapping_Product" files to help standarize words
- Ensuring dataset consistency

## 📊 Project Output & Analysis - Pivot Table & Pivot Chart
The output of these mini projects typically includes:
- **Total Sales per Category**
  - Kategori *Electronics* menyumbang pendapatan tertinggi sebesar RP 12,935,000. 
  <div align = "center">
    <img width="445" height="266" alt="image" src="https://github.com/user-attachments/assets/80cfa220-69f8-48d0-83b4-3f2c255013bf" />
  </div> 

- **Total Sales per Date / Trend Chart**
<div align = "center">
  <img width="450" height="252" alt="image" src="https://github.com/user-attachments/assets/08515610-15f0-4dc5-904c-8d384533024d" />
 </div>
  - Puncak tertinggi tren berada di bulan Februari sebesar Rp 10.050.000. 
  - Terjadi penurunan drastis dari bulan April ke Mei sebesar 66%.
  - Setelah analisis lebih lanjut, penurunan (*grafik putus-putus orange*) terjadi karena kurangnya data atau ketidakaturan durasi data. Dataset yang digunakan berakhir di tanggal *10 Mei 2024*, sehingga dapat dikatakan bahwa *data tersebut masih on-going atau Forecast*. <br>
<div align = "center">
  <img width="520" height="100" alt="image" src="https://github.com/user-attachments/assets/23a38fc8-a73c-4f79-a450-48543b852643" />
</div>
  - Setelah dilakukan analisa lebih lanjut dengan *forecasting*, didapatkan hasil bahwa pada bulan *Mei performa penjualan stabil sebesar Rp 9.889.000 atau 23.99%*, dan bahkan berpotensi menyamai rekor penjualan pada bulan Februari. ---- (After further analysis using forecasting, the results show that in May, sales performance was stable at IDR 9,889,000 or 23.99%, and even had the potential to match the sales record in February.) <br>
<div align = "center">
  <img width="230" height="246" alt="image" src="https://github.com/user-attachments/assets/f78fe043-a463-412d-b8e8-7f07d9f46cf7" />
</div>
  - Dilakukan Juga Analisa Perbandingan Tgl 1 - 10 April vs Mei. Didapatkan hasil, bahwa *total penjualan di bulan Mei lebih tinggi dibandingkan bulan April*. ---- (A comparative analysis was also conducted for April 1-10 vs. May. The results showed that *total sales in May were higher than in April*.)

- **Total Sales High vs Low**
  - Pada bulan Januari - Mei 2024 sekitar 85% produk yang diminati berasal dari produk dengan harga mahal. Di setiap bulannya minat konsumen tidak berubah, dapat disimpulkan bahwa produk dengan harga tinggi lebih mendominasi penjualan tiap bulan. ---- (From January to May 2024, around 85% of the most popular products were high-priced items. Consumer interest remained consistent each month, suggesting that high-priced products dominated sales every month.)
<div align = "center"
  <img width="417" height="275" alt="image" src="https://github.com/user-attachments/assets/b7afa68d-f460-46cf-bbc9-154c6b92ffb4" />
</div>

- **Total Sales per Region**
<div align = "center"
  <img width="459" height="359" alt="image" src="https://github.com/user-attachments/assets/7f6a3499-8869-4272-929c-d8a885878b91" />
</div>
  - Persentase penjualan tertinggi berasal dari daerah *West* yang mencapai angka 28%. ---- (The highest percentage of sales came from the *West* region, which reached 28%.)

- **Trend Harga Jual (Average per Unit)**
<div align = "center"
  <img width="853" height="693" alt="image" src="https://github.com/user-attachments/assets/5a690826-70d2-4724-b331-e435ab196485" />
</div>
  - Rata - rata penjualan bulan Januari - Mei 2024 mengalami peningkatan, dan puncaknya berada di bulan Mei sebesar Rp 145.500, sehingga penjualan produk meningkat secara bertahap setiap bulannya (*grafik batang orange*). ---- (Average sales from January to May 2024 increased, peaking in May at Rp 145,500, indicating a gradual monthly increase in product sales (*orange bar graph*).)

- **Total Sales of Each Category per Region**
<div align = "center"
  <img width="571" height="403" alt="image" src="https://github.com/user-attachments/assets/d27d56e6-b435-4964-9932-3c04787d1e09" />
</div>
  - Setiap daerah memiliki penjualan produk terbanyak dengan kategori tertentu. Dari grafik, kategori *Apparel* banyak menduduki daerah *East* ; daerah "West" kategoru "Footwear" paling disukai, dst. ---- (Each region has the highest sales of products in certain categories. From the graph, the “Apparel” category dominates the *East* region; the *West* region prefers the *Footwear* category, and so on.)<br>

<div align = "center"
  <img width="312" height="91" alt="image" src="https://github.com/user-attachments/assets/a3d12bab-1c28-4a8a-859c-4e5c1d89d44a" />
</div>
  - Apabila dilihat dari Sum of Quantity, kategori *Accessories* berada di urutan ke-3 dengan pembeli terbanyak dibandingkan kategori *Footwear*, tetapi total sales yang dihasilkan adalah yang paling rendah. Ini terjadi karena *harga unit price* *Accessories* lebih rendah dibanding kategori lain, sehingga grafik yang dihasilkan menujukkan *Accessories* berada di tingkat terendah penjualan. ---- (When viewed from the Sum of Quantity, the *Accessories* category ranks third with the most buyers compared to the *Footwear* category, but the total sales generated are the lowest. This is because the unit price of *Accessories* is lower than other categories, so the graph shows that *Accessories* has the lowest sales.)
  - Dari hal tersebut, tidak bisa dikatakan bahwa minat pembeli pada kategori *Accessories* di setiap wilayah itu rendah, akan tetapi, kita bisa meningkatkan penjualan kategori tersebut dengan beberapa cara seperti dilakukannya promosi melalui media sosial atau launching produk baru untuk menarik minat pelanggan lebih banyak dalam pembelian kategori tersebut. ---- (From this, it cannot be said that buyer interest in the *Accessories* category in each region is low. However, we can increase sales in this category in several ways, such as promoting it through social media or launching new products to attract more customers to purchase items in this category.)

## 🎯 Learning Outcome
After completing the Intermediate projects, the learner is able to:
- Prepare and clean datasets for analysis
- Apply intermediate Excel functions effectively
- Perform structured business analysis using Pivot Tables
- Build meaningful charts for reporting
- Translate data into actionable insights

## 📌 Notes
- Projects are based on practical business scenarios
- Focus is on analytical reasoning rather than automation
- This level bridges basic skills and intermediate analysis

## ✅ Status
✔  Completed

