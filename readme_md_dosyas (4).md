# 📌 HTML Özel Etiketler ve Kullanımları

### 1. `<a>` Etiketi ve `target` Özelliği
- **`target="_blank"`**: Bağlantıyı yeni bir sekmede açar.
- **`target="_self"`**: Bağlantıyı aynı sekmede açar (varsayılan değerdir).
- **`href="#id"`**: Sayfa içi çıpa bağlantısı kurarak ilgili ID'ye yönlendirir.
- **`href="mailto:..."`**: Doğrudan e-posta gönderme bağlantısı oluşturur.

---

### 2. `<fieldset>` ve `<legend>`
- **`<fieldset>`**: Form elemanlarını mantıksal gruplara ayırarak etrafına bir çerçeve çizer.
- **`<legend>`**: Bu çizilen çerçevenin başlığını belirler.

---

### 3. `<optgroup>` ve `<datalist>`
- **`<optgroup>`**: Açılır liste (`<select>`) içindeki seçenekleri kategorilere ayırmak için kullanılır.
- **`<datalist>`**: Bir metin kutusuna (`<input>`) otomatik tamamlama (öneri) listesi bağlar.

---

### 4. `<meter>` ve `<progress>` Arasındaki Fark
- **`<meter>`**: Bilinen belirli bir aralıktaki skaler ölçümü gösterir *(örneğin: disk doluluğu, bütçe riski, sınav puanı)*.
- **`<progress>`**: Bir işlemin tamamlanma veya ilerleme durumunu gösterir *(örneğin: dosya indirme %50 yüklendi)*.