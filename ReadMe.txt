Step 1: Double click pada solution SupermarketTuto.sln
Step2 : Di dalam file ini, copy and paste file smarketdb.mdf ke dalam solution
Step 3: Ketika visual studio telah dibuka, click/cari server explorer
Step 4: Lalu klik "Connect to Database"
Step 5: Cari location dari database file tersebut (harusnya disebelah kiri)
Step 6: Setelah berhasil ditambahkan, right click di file database dan klik 'property'
Step 7 : Copy connection string dan gantikan semua sqlconnection dengan address baru dibawah (sesuai laptop anda).

SqlConnection Con = new SqlConnection(@"Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=C:\Users\afwadmin\Documents\smarketdb.mdf;Integrated Security=True;Connect Timeout=30");
Gantikan apa yang ada di dalam "" dengan connection address baru.

Step8 : Project dapat di-run dengan baik
