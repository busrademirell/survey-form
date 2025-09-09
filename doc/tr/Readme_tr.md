 <p align="center">
  <a href="https://github.com/busrademirell/survey-form/blob/master/README.md">
    <img alt="downloads" src="https://img.shields.io/badge/English-En-blue" target="_blank" />
  </a>
  <a href="https://github.com/busrademirell/survey-form/blob/master/doc/tr/Readme_tr.md">
    <img alt="License: MIT" src="https://img.shields.io/badge/Turkish-Tr-red" target="_blank" />
  </a>
</p>

# Survey Form Project

---

## 🎯 Amaç

Bu proje,**TechConnect** müşterilerinden memnuniyet düzeylerini ve kullanım alışkanlıklarını öğrenmek amacıyla hazırlanmış çevrimiçi bir anket formudur ve hedefi, freeCodeCamp [Survey Form](https://survey-form.freecodecamp.rocks/) projesiyle işlevsel olarak benzer bir uygulama geliştirmektir.

---

## 🛠 Kullanılan Teknolojiler

- **HTML →** Form yapısı, etiketler ve semantik düzenlemeler
- **CSS →** Tasarım, renkler, tipografi ve responsive düzen

---

## 📚 Öğrendiklerim

- **For id class ->**
  For, label ile id değeri eşleşen form elemanını bağlar; etiket metnine tıklama alanı aktif hale getirir. Bir kişinin kimlik numarasına bakılması gibi, etiketin bağlanacağı kişiyi temsil eder.

  - id, elementin sayfadaki benzersiz kimliğidir ve yalnızca bir kez kullanılır.Kimlik numarası gibi tek ve kişiye özeldir.
  - class ise elementleri gruplandırmak için kullanılır; aynı class’a sahip elementler ortak CSS stillerini paylaşabilir.Meslek grubu gibi birden fazla kişi aynı grupta olabilir.

- **For ve id Kullanımı ->** Label ve input elemanları arasındaki ilişki, input elemanlarına id atayarak ve label etiketlerinde for kullanılarak sağlanır. Bu yöntem, erişilebilirlik ve kod okunabilirliği açısından en uygunudur.

- **Yüzde (%) ile rem farkı ->**
  **% (yüzde):** Element boyutlarını parent elementin boyutuna göre orantılı olarak belirlemek için tercih edilmiştir. Bu yaklaşım, responsive tasarımda esneklik sağlar.
  **rem (root em):** Font-size değerine göre boyutlandırma yapılmıştır. Bu yöntem, proje genelinde tutarlı tipografi ve boşluk (spacing) değerleri elde etmek için kullanılmıştır.

  - Örneğin CSS’de % ve rem birimlerinin farkını kıyafet ölçüsü ile açıklayabiliriz. % kullanımı, bir kıyafetin boyutunu ebeveynin ölçülerine göre ayarlamaya benzer; ebeveyn boyutu değiştikçe kıyafet de orantılı olarak değişir. Buna karşılık rem, standart bir ölçü birimi ile kıyafet dikmek gibidir; ölçü, her zaman root font-size değerine göre belirlenir ve ebeveyn boyutundan etkilenmez.

- **Responsive tasarım ->** Farklı cihazlarda uyumlu görünüm sağlamak için media query kullanımı, responsive tasarımın temel yöntemlerinden biridir ve kullanıcı deneyimini artırır.

- **Arka plan ve kontrast kullanımı ->** Linear-gradient ve opaklık değerleri kullanarak saydam ve estetik görünümler elde edilir, bu yöntem tasarımın görsel çekiciliğini artırır.

- **:root Kullanımı:** CSS’de :root ile global değişkenler tanımlanarak, bu değişkenler sayfa genelinde tutarlı ve kolay bir şekilde kullanılabilir.

- **overflow-x: hidden; Kullanımı:** Yatay kaydırmayı engelleyerek içeriğin yalnızca dikey yönde kaydırılmasına olanak tanır, bu sayede istenmeyen yatay taşmalar önlenir.

- **resize: vertical; Kullanımı:** Kullanıcıların yalnızca dikey yönde yeniden boyutlandırma yapmasına izin verir, yatay boyutlandırmayı engeller.

- **position: static; Kullanımı:** HTML öğelerinin varsayılan konumlandırma yöntemidir. Öğeler, sayfa akışına göre konumlandırılır ve top, left, right, bottom değerleri uygulanmaz.

- **position: relative; Kullanımı:** Öğenin konumu, normal akıştaki konumuna göre top, left, right, bottom değerleriyle ayarlanabilir. Diğer öğelerin konumunu etkilemez.

- **position: absolute; Kullanımı:** Öğeyi, en yakın konumlandırılmış (relative, absolute, fixed, sticky) üst öğeye göre konumlandırır. Normal sayfa akışından çıkar.

- **position: fixed; Kullanımı:** Öğeyi tarayıcı görünüm penceresine (viewport) göre sabitler. Sayfa kaydırılsa bile konumu değişmez.

- **position: sticky; Kullanımı:** Öğeyi, belirlenen bir kaydırma noktasına kadar normal akışta tutar, o noktadan sonra sabitler.

---

## 📷 Ekran Görüntüsü

![SurveyForm](surveyForm.gif)
