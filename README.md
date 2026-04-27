Görev 3: Dinamik Fiyatlandırma (Dynamic Pricing) Motoru
Senaryo: Sabit kâr marjları devri bitti. Rakiplerin fiyatları, elimizdeki stok durumu ve ürünün o anki talep yoğunluğuna göre fiyatları anlık güncelleyerek kârı maksimize edecek dinamik bir yapıya ihtiyacımız var.
Beklenti:Sen bir fabrika analiz uzmanısın. Senden beklentimiz .ipynb dosyasında basit bir "Dinamik Fiyat Fonksiyonu" yaz. Bu fonksiyon; "Mevcut Stok", "Son 24 Saatteki Görüntülenme (Talep)" ve "Rakip Fiyatı" gibi girdileri alarak, belirleyeceğin bir iş mantığıyla optimum yeni satış fiyatını döndürecek.

Algoritma Mantığı: Yeni fiyatın rastgele olmaması; talep arttığında fiyatı yükselten, stok şiştiğinde veya rakip fiyat kırdığında fiyatı düşüren anlamlı bir matematiğe dayanması.

Sınır ve Hata Yönetimi : Algoritmanın hiçbir koşulda ürünü "zararına (maliyetin altına)" satmaması için gerekli kontrollerin (exception/limit handling) yapılması.

Kod Verimliliği : Yazılan fonksiyonun temiz ve modüler olması.

Senaryo Testleri : Notebook içinde en az 3 farklı piyasa/stok senaryosu ile fonksiyonun test edilip sonuçların gösterilmesi.
