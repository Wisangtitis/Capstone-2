                                        **DON'T FORGET TO RUN ALL THE CELL FIRST!!!**

*************************************************************************************************************************
------------------------------------------ WELCOME TO MY SECOND PROJECT :) --------------------------------------------
*************************************************************************************************************************

-------------------------------------------------------------------------------------------------------------------------
                                    Capstone Project 2 - Crime in Boston Data Analytics
-------------------------------------------------------------------------------------------------------------------------

** Analisis data Crime in Boston

** Data ini merupakan rekaman dari laporan tindak kriminal yang ada di Boston dari tanggal 14 Juni 2015 hingga 3 September 2018.
Terdapat 17 Kolom default, dengan penjabaran sebagai berikut:
1. INCIDENT_NUMBER = Unique Value, berupa nomor pelaporan tindak kriminal.
2. OFFENSE_CODE = Kode OFFENSE tindak kriminal 
3. OFFENSE_CODE_GROUP = Penamaan Grup dari OFFENSE_CODE / jenis tindak kriminal
4. OFFENSE_DESCRIPTION = Deskripsi dari OFFENSE_CODE_GROUP / tindak kriminal apa yang dilaporkan
5. DISTRICT = Lokasi distrik kejadian tindak kriminal yang dilaporkan
6. REPORTING_AREA = Klasifikasi kode distrik
7. SHOOTING = Apakah dalam kejadian tindak kriminal tersebut dilaporkan ada penembakan senjata api atau tidak
8. OCCURED_ON_DATE = Waktu kejadian tindak kriminal
9. YEAR = Tahun kejadian tindak kriminal
10. MONTH = Bulan kejadian tindak kriminal
11. DAY_OF_WEEK = Hari kejadian tindak kriminal
12. HOUR = Pada pukul berapa kejadian tindak kriminal
13. UCR_PART = Kategori tindak kriminal berdasarkan UCR
14. STREET = Di jalan apa kejadian tindak kriminal
15. LAT = Lokasi Latitude / lintang kejadian tindak kriminal
16. LONG = Lokasi Longitude / bujur kejadian tindak kriminal
17. LOCATION = Berisi Lat dan Long yang dijadikan satu string (tidak dipisah Lat dan Long)

Dapat dikatakan bahwa semua kolom yang ada pada data ini memiliki jenis data nominal (bukan numerik), tidak ada angka/value yang bisa dihitung dari semua kolom (pengecualian pada kolom Lat Long yang menandakan lokasi).

Berdasarkan keterangan di atas, dapat diasumsikan bahwa semua kolom memiliki distribusi yang tidak normal (data nominal kategorik, value dari setiap kolom hanya label dan tidak melambangkan kedudukan/tingkatan tertentu).

** Outline dari Notebook:
- Importing Data
- Data Summary
- Check General Info Data
- Find and Handle the Anomalies
- Merge the Tables
- Big Question from me
- Exploring data
  - Tren annually
  - Most common types of Crime Incidents Reported
  - Most common Districts reported
  - Reports based on Location (by common type of incidents, also yearly and full timespan data)
  - Crime Incident report amount based on daytime - nighttime
  - Crime Incident report amount daily
 - Conclusions
 - Recommendations
 
 “You can have data without information, but you cannot have information without data” - Daniel Keys Moran
