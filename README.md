# Finance-Data-Analyst-Automation-Reporting-Assessment
Automation &amp; Reporting Assessment

Apa yang dilakukan pada code ini?

1. membaca setiap file sheet 'sales', 'expenses' dan maaping, dimana file tersebut berada pada gsheet yang berbeda.
* url_sales = "https://docs.google.com/spreadsheets/d/1sWAv1ehEnWCUM5mYBQJl1QvEjurVu08vsBIGO9PTPB4/export?format=csv&gid=1488886954"

* url_exp = "https://docs.google.com/spreadsheets/d/11Gq3ARHjhFfBewHqSNTVB-GBCZL1BBYaGzaBlRwFb7k/export?format=csv&gid=847693108"

* url_map = "https://docs.google.com/spreadsheets/d/1SMr-GJsLJvCU1jWHVPdF0ZU9rwdKwVIqrWA-NCDPZyo/export?format=csv&gid=185342484"

2. preraration : dimana dilakukan normalisasi data agar sesuai bentuk tipe datanya, melakukan cleansing data, melakukan cek diplikat

3. Mengkombinasi data sales dan expenses

4. Membuat Monthly P&L

5. melakukan visualisasi

setelah code ini jadi, kemudian dimasukan pada extention apps sciprt yang ada pada file sheet untuk laporan, dimana file sheet ini merupakan hasil final setelah code dirunning. Bisa di cek pada speadsheet berikut.

https://docs.google.com/spreadsheets/d/1RuVrPx1rzdZ6Uvs_qYG0XEFQ7-rWRFDHNdxSyP_tc1Q/edit?usp=sharing

pada spreadsheet, terdapat hasil running code yang sudah dimasukan kedalam appscript, dimana menambilkan untuk sheet "Merge" yang merupakan hasil merge 'Sales' dan 'Expenxes' dan terdapat sheet 'Insight' dan 'Monthly P&L' dimana menampikan

Revenue growth (MoM): 2.0%
Expense growth (MoM): -4.8%
Largest expense category (2025-09): 6400 = 36,870,389"
dan di sheet 'Monthly P&L' menampikan visualisasi dan tabelnya.
