# Modern Portfolio Website

Bu modern ve göz alıcı portföy websitesi, profesyonel çalışmalarınızı sergilemek için tasarlanmıştır. Responsive tasarım, modern animasyonlar ve temiz kod yapısı ile portfolyonuzu etkili bir şekilde sunabilirsiniz.

## Özellikler

- ✨ Modern ve minimalist tasarım
- 📱 Tam responsive yapı (tüm cihazlarda düzgün görüntülenir)
- 🌈 Göz alıcı animasyonlar ve geçişler
- 🧩 Modüler ve kolay özelleştirilebilir yapı
- 🔍 SEO dostu HTML yapısı
- 🔄 Portföy çalışmaları için filtreleme özelliği

## Başlangıç

Siteyi yerel ortamınızda çalıştırmak için şu adımları izleyin:

1. Bu repository'i klonlayın veya zip olarak indirin.
2. İndirdiğiniz dosyaları bir web sunucusuna yükleyin veya yerel bir web sunucusu üzerinde çalıştırın.
3. `index.html` dosyasını bir tarayıcıda açın.

## Özelleştirme

### Kişisel Bilgiler

Kişisel bilgilerinizi güncellemek için `index.html` dosyasını açın ve şu bölümleri kendi bilgilerinizle değiştirin:

- İsim, meslek ve tanıtım metni (Hero bölümü)
- Hakkımda bölümü
- İletişim bilgileri
- Sosyal medya linkleri

### Portföy Çalışmaları

Portföy çalışmalarınızı eklemek veya güncellemek için `index.html` dosyasındaki portfolio bölümünü düzenleyin:

```html
<div class="portfolio-item" data-category="kategori">
    <div class="portfolio-image">
        <img src="images/proje.jpg" alt="Proje Adı">
        <div class="overlay">
            <div class="overlay-content">
                <h3>Proje Adı</h3>
                <p>Proje Kategorisi</p>
                <a href="#" class="view-project">Projeyi İncele</a>
            </div>
        </div>
    </div>
</div>
```

### Renkler ve Stil

Renk şemasını ve diğer stil özelliklerini değiştirmek için `css/style.css` dosyasında `:root` bölümünü düzenleyin:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #4f46e5; 
    --accent-color: #7c3aed;
    --background-color: #f8fafc;
    --dark-background: #1e293b;
    --text-color: #334155;
    --light-text: #94a3b8;
    --white: #ffffff;
    --box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    --transition: all 0.3s ease;
    --border-radius: 8px;
}
```

### Görseller

Kendi görsellerinizi eklemek için:

1. `images` klasörüne kendi görsellerinizi yükleyin.
2. `index.html` dosyasında ilgili `<img>` etiketlerinin `src` özelliklerini kendi görsellerinizin yolları ile değiştirin.

## Dosya Yapısı

```
portfolio/
│
├── index.html              # Ana HTML dosyası
├── css/
│   └── style.css           # Ana CSS dosyası
├── js/
│   └── script.js           # JavaScript fonksiyonları
└── images/                 # Tüm görseller için klasör
    ├── profile-placeholder.jpg
    ├── project1.jpg
    ├── project2.jpg
    └── ...
```

## İletişim Formu

Mevcut iletişim formu, gerçek bir e-posta göndermek için bir back-end sisteme ihtiyaç duyar. Formunuzu çalışır hale getirmek için şu seçeneklerden birini kullanabilirsiniz:

1. **Formspree**: `<form>` etiketinin `action` özelliğini Formspree URL'niz ile değiştirin.
2. **Netlify Forms**: Sitenizi Netlify üzerinde barındırıyorsanız, form etiketine `data-netlify="true"` ekleyin.
3. **Kendi backend'iniz**: Form verisini işleyecek bir PHP veya Node.js backend kurun.

## Geliştirme

Bu siteyi daha da geliştirmek isterseniz:

1. Yeni bölümler ekleyebilirsiniz (blog, hizmetler, müşteri yorumları vb.).
2. Daha fazla animasyon veya geçiş efekti ekleyebilirsiniz.
3. Karanlık mod ekleyebilirsiniz.
4. Çoklu dil desteği ekleyebilirsiniz.

## Lisans

Bu site şablonu kişisel ve ticari kullanım için serbesttir. Ancak bu şablonu başkalarına atfetmeden tekrar dağıtamazsınız.

---

Tasarım ve geliştirme © 2023 