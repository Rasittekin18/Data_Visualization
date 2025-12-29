📊 Data Visualization:

Bu depo, veri görselleştirme dünyasına adım attığım ve farklı kütüphaneleri kullanarak çeşitli veri setlerini analiz ettiğim kapsamlı bir öğrenme sürecini içermektedir. Kurs boyunca veriyi anlamlandırmak, desenleri keşfetmek ve bilgiyi görsel bir hikayeye dönüştürmek üzerine çalışmalar gerçekleştirdim.

🛠️ Kullanılan Araçlar ve Kütüphaneler
Proje kapsamında veriyi görselleştirmek için popüler ve güçlü Python kütüphanelerinden yararlanılmıştır:

    Temel Görselleştirme: Matplotlib, Seaborn, ggplot, Pandas Visualization

    İnteraktif Grafikler: Plotly, Bokeh, Pygal

    Özel Alanlar: * Kayıp Veri Analizi: Missingno

    Ağ Analizi: NetworkX

    Coğrafi Veriler: Geoplotlib

    Diğer: Leather, Gleam

📂 Analiz Edilen Veri Setleri

Kurs süresince aşağıdaki gerçek dünya veri setleri üzerinde uygulamalar yapılmıştır:

1. Iris Species: Botanik veri analizi.

2. Significant Earthquakes: Dünya genelindeki önemli depremlerin incelenmesi.

3. Aerial Bombing Operations (WW2): 2. Dünya Savaşı hava bombardıman operasyonları.

4. Weather Conditions (WW2): Savaş dönemindeki hava koşullarının analizi.

5. World University Rankings: Küresel üniversite sıralamaları.

6. Fatal Police Shootings in the US: ABD'deki polis müdahaleleri verileri.

7. Titanic: Klasik hayatta kalma analizi ve demografik veriler.
<br><br>
<br><br>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🎨 1. Veri Görselleştirme: Seaborn ile Derin Dalış (Seaborn)

Bu bölümde, Python'un en güçlü görselleştirme kütüphanelerinden biri olan Seaborn kullanılarak karmaşık veri setleri üzerinde detaylı analizler yapılmıştır.

📈 Kullanılan Teknikler ve Grafik Türleri:

    Bar Plot: Kategorik verilerin sayısal değerlerle karşılaştırılması (Örn: Eyaletlere göre fakirlik oranları).

    Point Plot: Değişimlerin ve eğilimlerin noktalar üzerinden takibi.

    Joint Plot: İki değişken arasındaki ilişkiyi hem dağılım hem de yoğunluk açısından inceleme (Scatter + Histogram).

    Pie Chart: Veri setindeki oranların dairesel gösterimi (Örn: Öldürülen kişilerin ırk dağılımı).

    LM Plot: Doğrusal regresyon hattı ile değişkenler arasındaki korelasyonun analizi.

    KDE Plot (Kernel Density Estimation): Veri yoğunluğunun sürekli bir çizgi ile görselleştirilmesi.

    Violin Plot: Veri dağılımının ve yoğunluğunun (Box plot ve KDE birleşimi) gösterilmesi.

    Heatmap: Veriler arasındaki korelasyon (ilişki) matrisinin renklerle ifade edilmesi.

📋 Uygulanan Veri Setleri:

- Fatal Police Shootings in the US: Bu veri seti üzerinde fakirlik oranları, lise mezuniyet oranları ve ırksal demografi gibi birçok farklı açıdan görselleştirme çalışılmıştır.
<br><br>
<br><br>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


📊 2. İnteraktif Görselleştirme: Plotly ile Etkileşimli Analizler (Plotly_0)

Bu aşamada, statik grafiklerin ötesine geçerek kullanıcı etkileşimine izin veren (zoom, hover, filtreleme) Plotly kütüphanesi kullanılmıştır. Analizler sırasında "Dünya Üniversite Sıralamaları" veri seti temel alınmıştır.

🚀 Kullanılan Grafik Türleri ve Teknikler:

    Line Charts: Üniversitelerin yıllara göre alıntı ve öğretim skorlarının karşılaştırılması.

    Scatter Charts: Farklı yıllardaki üniversite sıralamaları arasındaki korelasyonun incelenmesi.
    
    Bar Charts: En iyi üniversitelerin çeşitli kriterlere göre (öğretim, alıntı vb.) kıyaslanması.
    
    Pie Charts: Üniversitelerin dünya sıralamasındaki oranlarının ve sayısal dağılımlarının görselleştirilmesi.
    
    Bubble Charts: Üçüncü bir değişkenin (üniversite skoru gibi) daire boyutuyla temsil edildiği gelişmiş dağılım grafikleri.
    
    Histogram: Üniversitelerin öğrenci-öğretmen oranları gibi sayısal verilerin dağılım sıklığı.
    
    Word Cloud: Veri setindeki metinsel yoğunlukların (örneğin üniversite isimleri veya ülkeler) görselleştirilmesi.
    
    Box Plots: Verilerin istatistiksel dağılımı ve aykırı (outlier) değerlerin tespiti.
    
    Scatter Plot Matrix: Birden fazla değişken arasındaki tüm olası ikili ilişkilerin aynı anda görülmesi.

    Inset Plots: Büyük bir grafiğin içine daha detaylı bir alt grafik ekleme tekniği.
    
    3D Scatter Plot: Verilerin üç boyutlu uzayda (z-ekseni dahil) görselleştirilmesi.
    
    Multiple Subplots: Aynı figür içerisinde farklı veri görünümlerinin yan yana veya alt alta sergilenmesi.

📋 Uygulanan Veri Seti:

- World University Rankings: Üniversitelerin dünya çapındaki başarı kriterlerini içeren kapsamlı veri seti.
<br><br>
<br><br>


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🗺️ 3. Coğrafi ve İnteraktif Haritalama: Plotly Choropleth (Plotly_1)

Bu bölümde, verilerin dünya haritası üzerinde nasıl görselleştirileceği ve zaman serisi bazlı animasyonların nasıl oluşturulacağı üzerine odaklanılmıştır.

🌍 Öğrenilen Teknikler ve Haritalama Türleri:

    Choropleth Maps: Ülkelerin veya bölgelerin belirli bir istatistiğe (Örn: GDP, Okur-yazarlık oranı) göre renk tonlarıyla ayrıştırılması.
    
    Animated Maps: Verilerin yıllara göre değişimini gösteren zaman sürgülü (slider) animasyonlu dünya haritaları.
    
    Geographical Data Processing: Ülke isimlerinin ve kodlarının harita üzerinde doğru konumlandırılması için veri manipülasyonu.
    
    Custom Tooltips: Harita üzerinde bir ülkenin üzerine gelindiğinde o ülkeye özel detaylı bilgilerin (hover info) gösterilmesi.

📋 Uygulanan Veri Setleri:

- World University Rankings (Geographical): Üniversitelerin bulunduğu ülkelerin akademik performans skorlarının dünya haritası üzerindeki dağılımı.

- Aerial Bombing Operations (WW2): İkinci Dünya Savaşı sırasındaki hava operasyonlarının lokasyon bazlı görselleştirilmesi.
<br><br>
<br><br>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


⏳ 4. Zaman Serisi ve Karmaşık Veri Analizi: Plotly Advanced  (Plotly_2)

Bu bölümde, zaman damgalı verilerin nasıl işleneceği ve tarihsel olayların veri görselleştirme yoluyla nasıl hikayeleştirileceği üzerine çalışılmıştır.

📉 Öğrenilen Teknikler ve Görselleştirme Stratejileri:

    Time Series Analysis: Verilerin zaman içindeki değişimini gözlemlemek için özelleştirilmiş çizgi grafikleri.
    
    Bubble Charts with Time: Zaman ekseninde değişen balon grafikleri ile üç farklı değişkenin (tarih, miktar ve tür) eş zamanlı analizi.
    
    Data Aggregation for Visualization: Büyük veri setlerinin (WW2 Bombardıman verileri gibi) görselleştirilmeden önce tarih ve kategori bazlı gruplandırılması.
    
    Multiple Plot Layouts: Farklı saldırı tiplerinin veya ülkelerin performanslarının yan yana (subplots) karşılaştırılması.

📋 Uygulanan Veri Setleri:

- Aerial Bombing Operations (WW2): İkinci Dünya Savaşı'ndaki hava saldırılarının tarihlere, ülkelere ve hedef türlerine göre detaylı dökümü.

- Weather Conditions (WW2): Savaş dönemindeki hava durumu istasyonlarından gelen verilerin analizi.
<br><br>
<br><br>

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🧪 5. Nadir Kullanılan Görselleştirme Araçları (Rare Visualization Tools)

Veri biliminde sıklıkla kullanılan temel grafiklerin ötesine geçerek, keşifsel veri analizi (EDA) sürecini zenginleştiren ve veri setindeki gizli kalmış detayları ortaya çıkaran özel kütüphaneler incelenmiştir.

🛠️ İncelenen Özel Kütüphaneler ve Teknikler:

    Missingno: Veri setindeki eksik verilerin (missing values) dağılımını ve yoğunluğunu hızlıca tespit etmek için kullanılmıştır.
    
    Parallel Plots (Pandas): Çok boyutlu verileri (örneğin Iris veri setindeki 4 farklı özellik) aynı anda görselleştirerek sınıflar arasındaki ayrımı gözlemleme.
    
    NetworkX: Veriler arasındaki ağ yapılarını ve ilişkisel bağlantıları (Nodes & Edges) görselleştirme.
    
    Venn Diagram (Matplotlib-Venn): Gruplar arasındaki kesişim ve farkları küme diyagramları ile ifade etme.
    
    Donut Chart: Pie chart'ın daha modern bir versiyonu olarak veri oranlarını gösterme.
    
    3D Scatter Plots (Plotly): Üç farklı sayısal değişkenin birbirine göre konumunu 3 boyutlu uzayda inceleme.

📋 Uygulanan Veri Setleri:

- Iris Species: Botanik verilerinin çok boyutlu analizi.

- Titanic: Yolcu verilerindeki eksik bilgilerin missingno ile analizi.
