# Text Generation Strategies

Bu proje, dil modellerinde metin üretimi için kullanılan farklı stratejilerin teorik açıklamalarını ve Python uygulamalarını içermektedir. Aşağıdaki yöntemler detaylı bir şekilde incelenmiştir:

1. **Beam Search**
2. **Greedy Search**
3. **Sampling (Top-k ve Top-p)**

## Proje İçeriği

### 1. Beam Search
Beam Search, olası tüm dizileri paralel olarak değerlendirerek en iyi metni oluşturmayı hedefler. Beam width parametresi, kaç alternatif dizinin değerlendirileceğini kontrol eder.

- **Avantajlar:**  
  - Daha yüksek doğruluk ve kalite.
- **Dezavantajlar:**  
  - Yüksek hesaplama maliyeti.

**İçerik:**  
- Beam Search algoritmasının detaylı açıklaması.
- Adım adım Python uygulamaları.

Notebook dosyasına göz atmak için: [Beam_Search.ipynb](Beam_Search.ipynb)

---

### 2. Greedy Search
Greedy Search, her adımda yalnızca en yüksek olasılığa sahip kelimeyi seçer. Hızlı bir yöntem olmakla birlikte global optimum bulma olasılığı düşüktür.

- **Avantajlar:**  
  - Basit ve hızlı.
- **Dezavantajlar:**  
  - Çeşitlilik düşük.
  - Yerel optimuma takılabilir.

**İçerik:**  
- Greedy Search algoritmasının açıklaması.
- Python ile uygulanmış örnekler.

Notebook dosyasına göz atmak için: [Greedy_Search.ipynb](Greedy_Search.ipynb)

---

### 3. Sampling (Top-k ve Top-p)
Sampling yöntemleri, rastgelelik ekleyerek daha çeşitli metinler üretir.

- **Top-k Sampling:**  
  Sadece en yüksek olasılığa sahip \( k \) kelimeler dikkate alınır.
- **Top-p (Nucleus) Sampling:**  
  Olasılıkların toplamı belirli bir eşik değerine (\( p \)) ulaşana kadar kelimeler seçilir.

- **Avantajlar:**  
  - Çeşitlilik ve yaratıcılık sağlar.
- **Dezavantajlar:**  
  - Rastgelelik nedeniyle tahmin edilebilirlik azalabilir.

**İçerik:**  
- Sampling algoritmalarının açıklaması.
- Top-k ve Top-p uygulama örnekleri.

Notebook dosyasına göz atmak için: [Sampling,_Top_k_and_Top_p.ipynb](Sampling,_Top_k_and_Top_p.ipynb)


