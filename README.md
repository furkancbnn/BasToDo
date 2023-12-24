<!-- Detaylandırılmış JS açıklama:

1. **HTML Yapısını Oluştur:**
   - Gerekli HTML elementlerini oluştur: Bir başlık (h1), bir form içinde bir metin girişi (input) ve iki adet buton (submit) bulunmalıdır. Ayrıca, bir liste için bir `div` container ekleyin.

2. **JavaScript Dosyasını Bağla:**
   - HTML dosyan ile JavaScript dosyanı doğru bir şekilde bağla. Script etiketini kullanarak JavaScript dosyanı belirtmeyi unutma.

3. **Değişken İsimlendirmesi:**
   - İlgili HTML elementlerine JavaScript'ten erişebilmek için değişkenlere uygun isimleri ver. Örneğin, "addToDo" butonu için bir değişken oluştur.

4. **Olayları Belirle:**
   - "Add" ve "Clear" butonlarına tıklama olaylarını (click events) belirle. Bu olaylar tetiklendiğinde çalışacak fonksiyonları belirle.

5. **JavaScript Fonksiyonunu Oluştur:**
   - Yukarıda belirlenen olaylarda çalışacak fonksiyonları oluştur.
   - "Add" butonuna tıklandığında çalışacak fonksiyon:
      - Yeni bir `p` (paragraf) elementi oluştur.
      - Oluşturulan `p` elementini `toDoContainer` içine ekle.
      - `inputText` içindeki değeri bu `p` elementinin içeriği olarak ayarla.
      - `inputText` içeriğini temizle.
      - Stil ekleyerek görünümü özelleştir.

6. **"Clear" Butonunu İşle:**
   - "Clear" butonuna tıklanınca çalışacak fonksiyon:
      - `toDoContainer` içindeki `p` elementini kaldır. -->

---

# ToDo List Uygulaması

## Değişkenler

- `addToDoButton`: "Add" butonunu temsil eden HTML öğesi.
- `toDoContainer`: ToDo öğelerinin listelendiği konteyner div'i.
- `inputText`: Kullanıcının yeni görevleri eklemek için kullandığı metin kutusu.
- `clearToDoButton`: "Clear" butonunu temsil eden HTML öğesi.

## `addToDoButton` Olayı

- Kullanıcı "Add" butonuna tıkladığında gerçekleşir.
- Yeni bir `<p>` öğesi oluşturulur ve bu öğe `toDoContainer` içine eklenir.
- `<p>` öğesinin içeriği, `inputText` içindeki değere ayarlanır.
- Yeni görevin üzerine tıklandığında görev çizgili hale gelir.
- Göreve çift tıklandığında görev silinir.
- Göreve tıklandığında görevin rengi kırmızıya döner.

## `clearToDoButton` Olayı

- Kullanıcı "Clear" butonuna tıkladığında gerçekleşir.
- `toDoContainer` içindeki tüm `<p>` öğeleri silinir, yani tüm görevler temizlenir.
#   B a s i c T o D o  
 #   B a s i c T o D o  
 #   B a s i c T o D o  
 #   B a s T o D o  
 