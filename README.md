# ROYAUME DE BRETONNIE (bretonnia.org)
## Royale Bibliothèque, Héraldique Sacrée & [BRE] Archives Officielles

Bu proje; Warhammer Fantasy Bretonnia evreni, 480+ aktif üyeli köklü **[BRE] (Bretonnia)** klanı ve kadim Avrupa kraliyet mirası standartlarında (*coronasibericas.com* estetiğinde) tasarlanmış ve kodlanmış kurumsal arşiv platformudur.

---

### 🏹 1. Royal Archers (Kraliyet Okçuları) Bağımsız Statüsü
- **İsim Değişikliği:** Eski "Archers" birliğinin adı resmen **"Royal Archers"** olarak güncellendi.
- **Bağımsız Hiyerarşi:** Herrimaults alt hanesi olma durumu tamamen kaldırıldı. Şemada ve arşivde bağımsız, tam prestijli bir kraliyet alayı statüsüne kavuşturuldu.
- **Kaptanlar:** Kaptanları Tobié "Jeste-roche" & [DrpyB] (Royal Archers Kaptanları).
- **Rozet & Taktik Rol:** `Bağımsız Kraliyet Alayı` • `Bağımsız Menzilli Vurucu Güç & Elit Uzun Yay Alayı`.
- **Ağ Tasarımı:** Soy ağacında alt hane bağlantı çizgileri kaldırılmış olup bağımsız prestijli kart formatında sergilenmektedir.

---

### 🛡️ 2. Gasconnie & Couronne Hanedanlık Güncellemeleri
- **Gasconnie Lordluğu Sancağı:** Yeni resmi heraldik arma (kırmızı-mavi yarılı kalkan üzerinde ortada dik altın kraliyet kılıcı ve iki yanında altın zambaklar / fleur-de-lis) `gasconnie.png` olarak sisteme işlendi.
- **Couronne Lordluğu Lideri:** Couronne Lordluğu'nun lideri **Roland le Maréchal** olarak güncellendi.
- **Gasconnie Lordluğu Lideri:** Huebald de Gasconnie (Krallığın Kralı ve Gasconnie Lordu).

---

### 🎨 3. Dinamik Tema Mimarisi, Arka Plan & Otomatik Yüksek Kontrast
Header'ın sağ aksiyon barındaki tema butonu ve açılır menüsü üzerinden 3 asil tema arasında anında geçiş sağlanır. Tüm renk geçişleri CSS değişkenleri (`--bg-primary`, `--text-primary`, `--text-secondary`, `--accent-gold`) üzerinden doğrudan `document.body` seviyesinde senkronize edilir:

1. **Royale Archive (Varsayılan Koyu Tema):**
   * Zemin: `#141414` (Derin Antrasit)
   * Ana Metin: `#F9F7F2` (Parşömen Beyazı)
   * İkincil Metin: `#D1CCC0`
   * Vurgu: `#B89758` (Eskitme Altın)
2. **Parchment Palace (Açık Tema):**
   * Zemin: `#F9F7F2` (Parşömen Keten)
   * Ana Metin: `#141414` (Derin Antrasit)
   * İkincil Metin: `#3D3A35`
   * Vurgu: `#4A1C1C` (Kraliyet Bordosu)
3. **Bloody Mousillon (Koyu Bordo Tema):**
   * Zemin: `#4A1C1C` (Kraliyet Bordosu)
   * Ana Metin: `#F9F7F2` (Parşömen Beyazı)
   * İkincil Metin: `#E5DEC9`
   * Vurgu: `#B89758` (Eskitme Altın)

---

### 🛡️ 4. Armorials & Dükalık Detay Paneli Sabit Kontrast Kuralı
1. **Sol Şema Alanı (`#armorialsTreeContainer`):** Tema değişimlerinden bağımsız olarak soy ağacı sol matris alanı kendi sabit asil parşömen tonunda (`#F4EFE6`) ve koyu okunaklı tipografisiyle (`#141414`) sabit kalır.
2. **Sağ Dükalık Detay Paneli (`#duchiesDetailPanel`):** Detay panelinin arka planı her temada **beyaz (`#FFFFFF`)** kalır; üzerindeki tüm unvanlar, metinler ve açıklamalar koyu antrasit (`#141414`) ve kraliyet bordosu (`#4A1C1C`) tonlarında net okunur.

---

### 📁 Proje Dosyaları ve İndirme

Tüm proje yerel çalışma alanınızda eksiksiz olarak hazırdır:
- **Ana Dizin:** `C:\Users\lucan\.gemini\antigravity\scratch\bretonnia\`
- **Ana Sayfa:** [index.html](file:///C:/Users/lucan/.gemini/antigravity/scratch/bretonnia/index.html)
- **Hazır Dağıtım Arşivi:** [bretonnia_website.zip](file:///C:/Users/lucan/.gemini/antigravity/scratch/bretonnia/bretonnia_website.zip) *(4.28 MB)*
