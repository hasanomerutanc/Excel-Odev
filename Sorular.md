
### 📝 Soru 1
Ödev ekinde verilen Excel dokümanındaki **"Soru-1"** isimli Excel sayfasının **A sütununda** "0" ile "4" arasında "0.1" birim artışlı rakamları yerleştirin ve **X** başlığı verin. 

**B sütununda** ise bu sayıların ortalaması "2" olan üstel dağılım değerlerini hesaplayıp üzerine gürültü faktörü ekleyin ve **Y** başlığı verin. Burada gürültü faktörü `[0;0.01]` aralığında düzgün dağılımdan gelen bir rassal sayı olsun. 

Daha sonra bu iki sütundaki değerleri kullanarak **"Yumuşak çizgileri olan dağılım"** grafiğini çizdirin. Eksen sınırlarını X ve Y değerlerini sırasıyla `[0; 4]` ve `[0; 2]` aralığında ölçeklendirin. Bu grafik için verileri en iyi tanımlayan üstel **"eğilim çizgisini"** ekleyip, grafik üzerinde denklemi ve bu denkleme ait $R^2$ değerini görüntüleyin.

---

### 📝 Soru 2
**"Soru-2"** isimli Excel sayfasında 5x5'lik bir matris rassal olarak oluşturulmakta ve bu matrisin tersi alınarak kendisi ile çarpılmaktadır. 

Bu amaçla;
* Sayfanın **"B1"** hücresine alt sınır, **"B2"** hücresine üst sınır bilgisi kullanıcı tarafından elle girilecektir.
* **"D2:H6"** hücrelerindeki değerler `[alt sınır - üst sınır]` aralığında rassal tamsayılardan elde edilecektir.
* **"J2:N6"** hücrelerinde "D2:H6" hücrelerinde sunulan matrisin tersi bulunacaktır.
* **"P2:T6"** hücrelerinde ise "J2:N6" ve "D2:H6" aralığında belirtilen iki matrisin çarpımı bulunacaktır.

*Not: Ters matrisin içeriği küsuratlı sayılardan oluşacağı için noktadan sonra 4 haneye kadar ekranda görünmelidir.*

---

### 📝 Soru 3
**"Soru-3"** isimli Excel sayfasında bir simülasyon çalışması sonucunda elde edilen 3 alternatif sistemden gözlemlenen değerler ve bu değerlerin ANOVA sonuçları hesaplanmak istenmektedir.

Bu amaçla, **A1, B1 ve C1** hücrelerine sırasıyla **"Deney-1"**, **"Deney-2"** ve **"Deney-3"** başlıklarını yazın. **A2, B2 ve C2** hücrelerinden itibaren aşağıya doğru 50'şer adet rassal sayıyı sırasıyla aşağıdaki bilgileri kullanarak üretin:

* **Deney-1:** Ortalaması 5, standart sapması 1 olan normal dağılımdan, çekirdek değerini öğrenci numaranızın son 4 hanesi kabul ederek 50 rassal değişken üretin.
* **Deney-2:** Ortalaması 6, standart sapması 1 olan normal dağılımdan, çekirdek değerini öğrenci numaranızın son 4 hanesi kabul ederek 50 rassal değişken üretin.
* **Deney-3:** Ortalaması 10, standart sapması 1 olan normal dağılımdan, çekirdek değerini öğrenci numaranızın son 4 hanesi kabul ederek 50 rassal değişken üretin.

Üretilen bu değerleri kendi içerisinde **"ANOVA-Tek Etken"** testine tâbi tutun ve sonuç raporunun **F1** hücresinden itibaren hazırlanmasını sağlayın.

---

### 📝 Soru 4
Aşağıdaki matematiksel model için **"Soru-4"** isimli Excel sayfasında modeli kurun ve optimal çözümü elde edin.

$$\text{Min } Z = X_1 + X_2 + X_3 + X_4 + X_5 + X_6$$

**Kısıtlar (S.T.):**
* $X_1 + X_6 \ge 6$
* $X_1 + X_2 \ge 9$
* $X_2 + X_3 \ge 13$
* $X_3 + X_4 \ge 5$
* $X_4 + X_5 \ge 15$
* $X_5 + X_6 \ge 5$
* $X_1, X_2, X_3, X_4, X_5, X_6 \ge 0 \text{ ve } \text{Tamsayı}$

---

### 📝 Soru 5
**"Soru-5"** isimli sayfada ülkemizin illerinin [2000-2025] tarihleri arasındaki nüfus sayım bilgileri bulunmaktadır. **"İl-Bölge"** isimli sayfada ise hangi ilin hangi bölgeye ait olduğu bilgisi bulunmaktadır.

**"Soru-5"** isimli sayfada, mevcut sütunlara ek olarak **"D" sütununa "Bölge"** başlıklı bir sütun daha ekleyin ve bu sütunda her bir ilin hangi bölgede olduğu bilgisini formül yardımıyla gösterin.

---

### 📝 Soru 6
**"Soru-5"** isimli Excel sayfasındaki bilgileri kullanarak yeni bir sayfada **PivotTable** oluşturun ve sayfanın adını **"Soru-5 (Pivot)"** şeklinde değiştirin.

Bu pivot tablonun satırlarında **"Bölge"**, sütunlarında ise **"Yıl"** bilgisi bulunsun. Tabloda ise her bölgenin ilgili yıldaki toplam nüfus bilgisi raporlansın.

---

### 📝 Soru 7
**"Soru-6"** için hazırladığınız pivot tablo için **3 Boyutlu Sütun** grafiğini hazırlayın.

Bu grafiği yeni bir sayfaya taşıyın ve sayfanın adını **"Soru-5 (Grafik)"** şeklinde değiştirin. Grafikte bölgeler nüfuslarına göre soldan sağa, büyükten küçüğe sıralanarak gösterilsin.
