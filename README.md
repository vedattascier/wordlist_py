
# Kişiye Özel Wordlist Oluşturma Aracı

Bu proje, kişiye özel bir wordlist oluşturmanıza yardımcı olur. Python betiğimiz ve bir shell betiği içerir. Python betiği, kurban bilgilerini toplar ve bir dosyaya kaydeder. Shell betiği ise Python betiğini çalıştırmak için kullanılabilir.

## Özellikler

- **Kurbanın Adı**
- **Kurbanın Soyadı**
- **Kurbanın Çocuğunun Adı**
- **Kurbanın Eşinin veya Sevgilisinin Adı**
- **Kurbanın Yaşadığı İl**
- **Kurbanın Yaşadığı İlçe**
- **Kurbanın Kullanıcı Adı**
- **Kurbanın Çocuğunun TC No**
- **Kurbanın Köpeğinin Adı**
- **Kurbanın Plaka**
- **Kurbanın Telefonu**
- **Doğum Tarihi** (isteğe bağlı)
- **Listene en çok kullanılan parolalar**

## Kurulum

1. **Python Kurulumu**

   Python 3.x sürümünü [Python'un resmi sitesinden](https://www.python.org/downloads/) indirebilirsiniz.

2. **Projeyi İndirme**

   Bu projeyi GitHub'dan indirebilir veya klonlayabilirsiniz:

   ```bash
   git clone https://github.com/your-repository-url.git
   ```

3. **Gerekli Paketlerin Yüklenmesi**

   Proje bir Python betiği içerdiği için, gerekli Python modüllerini yükleyin:

   ```bash
   pip install -r requirements.txt
   ```

## Kullanım

### Python Betiğini Çalıştırma

1. Python betiğini doğrudan çalıştırmak için terminal veya komut istemcisinde aşağıdaki komutu kullanın:

   ```bash
   python3 w.py
   ```

2. Betik çalıştığında, aşağıdaki bilgileri girmeniz istenecektir:
   - **Kurbanın Adı**
   - **Kurbanın Soyadı**
   - **Kurbanın Çocuğunun Adı**
   - **Kurbanın Eşinin veya Sevgilisinin Adı**
   - **Kurbanın Yaşadığı İl**
   - **Kurbanın Yaşadığı İlçe**
   - **Kurbanın Kullanıcı Adı**
   - **Kurbanın Çocuğunun TC No**
   - **Kurbanın Köpeğinin Adı**
   - **Kurbanın Plaka**
   - **Kurbanın Telefonu**
   - **Doğum Tarihi** (isteğe bağlı)
   - **Listene en çok kullanılan parolalar**


3. Bilgiler, kurban adıyla aynı ada sahip bir `.txt` dosyasına kaydedilecektir.

### Shell Betiğini Kullanma

1. `wordlist.sh` betiğini çalıştırmak için terminal veya komut istemcisinde aşağıdaki komutu kullanın:

   ```bash
   bash wordlist.sh
   ```

   Bu betik, Python betiğini çalıştırır ve kullanıcıdan gerekli bilgileri toplar.

## Notlar

- Doğum tarihi 0, 8 veya 10 karakter uzunluğunda olabilir. Bu alanı boş bırakabilirsiniz.
- Terminal başlığı, betiğin çalıştığı sürede "vedattascier" olarak ayarlanır.

## Katkıda Bulunanlar

- **Vedat Taşçıer** - [GitHub Profiliniz](https://www.vedattascier.com/#iletisim))

## Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.

## İletişim

Sorularınız veya önerileriniz için lütfen [Vedat Taşçıer](mailto:your-email@example.com) ile iletişime geçin.
```

### Açıklamalar:

- **Başlık ve Özellikler:** Projenin genel açıklaması ve özellikleri.
- **Kurulum:** Python kurulumu ve projeyi indirme adımları.
- **Kullanım:** Python betiği ve shell betiği ile nasıl çalışılacağı.
- **Notlar:** Önemli bilgiler ve uyarılar.
- **Katkıda Bulunanlar ve Lisans:** Projeye katkıda bulunan kişi ve lisans bilgileri.
- **İletişim:** İletişim bilgileri.

Bu `README.md` dosyası, projeyi kullanacak kişilere nasıl kuracaklarını ve çalıştıracaklarını net bir şekilde açıklar.
