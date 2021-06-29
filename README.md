## Flask kurulumu ve ilk uygulama
# Flask kurulumu
İlk olarak  flaskı kurmak için Komut Sistemini yönetici olarak çalıştırarak "pip install Flask" komutunu çalıştırdım. Bu şekilde fşaskı yüklemiş oldum.
Uygulamaları geliştirmek için  Visual Studio Code kullandım.
# İlk Uygulama
Uygulamamı oluşturduktan sonra
"	from flask import Flask" ile Flask Framework dahil ettim.
"app = Flask(__name__)" ile app adında uygulamayı oluşturdum.
"	if __name__ ==”__main__:" ile satırı ile uygulamamızı kontrol ettim.
" app.run(debug =True)" ile satırı ile uygulamayı çalıştırdım.
"def index():
    return "Merhaba Dünya" " ile bir decoreter mantığı ile bir request yaptım. Ve bu request karşılık fonksiyon yardımı ile bir response değeri döndürdüm.
    
Burada çok dikkat etmeniz gereken bir yer var.  @app.route(“/”)  ile request yaptıktan hemen sonra hemen o requst kaşılık gelecek response değerini döndüren fonksiyonu yazmamız gerekiyor.


