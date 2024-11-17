# WINDOWS KOMUTLARI
![GÖRSEL](/win%20resim/WİN.png)


- ###  Windows, Microsoft tarafından geliştirilen bir işletim sistemidir ve dünya genelinde en yaygın kullanılan işletim sistemlerinden biridir. İlk kez 1985 yılında tanıtılan Windows, kullanıcı dostu grafiksel arayüzü ile kişisel bilgisayarlarda büyük bir devrim yapmıştır. 
- ###  Dosya yönetimi, çoklu görev çalıştırma, geniş yazılım desteği ve güvenlik özellikleri gibi temel işlevlerle birlikte gelir. Günümüzde Windows 11 gibi modern sürümleri, dokunmatik ekran desteği, bulut entegrasyonu ve oyun performansı gibi yenilikçi özellikler sunarak kullanıcı deneyimini daha da ileri taşımaktadır. Özellikle bireysel kullanıcılar, işletmeler ve eğitim kurumları tarafından tercih edilen Windows, iş, eğlence ve yaratıcılık için çok yönlü bir platform sağlar.
## Dosya ve Klasör İşlemleri

### 1.`dir` Komutu

- Windows'ta `dir` komutu, belirli bir dizindeki dosya ve klasörlerin listesini görüntülemek için kullanılır.

### Örnek Kullanım

```bash
dir
```
![görsel](/win%20resim/dir.png)

### 2.`cd`Komutu

- Windows'ta `cd` (Change Directory) komutu, komut istemcisi içinde mevcut çalışma dizinini değiştirmek için kullanılır.

### Örnek Kullanım

```bash
cd C:\Users\Username\Documents
```
![görsel](/win%20resim/cd%20.png)

### 3.`cd..`Komutu

- Windows'ta `cd..` komutu, mevcut çalışma dizininden bir üst dizine geçmek için kullanılır. Bu, kullanıcıların dizin yapısında geri gitmesini sağlar.

### Örnek Kullanım

Varsayılan olarak **C:\Users\Username\Documents** dizinindesiniz:

```bash
cd..
```
![görsel](/win%20resim/cd...png)

### 4.`mkdir`Komutu

- Windows'ta `mkdir` (Make Directory) komutu, yeni bir klasör oluşturmak için kullanılır.

### Örnek Kullanım

Aşağıdaki komut, "YeniKlasor" adında bir klasör oluşturur:

```bash
mkdir YeniKlasor
```
![görsel](/win%20resim/mkdir.png)
### 5.`rmdir` Komutu

- Windows'ta `rmdir` (Remove Directory) komutu, belirtilen bir klasörü silmek için kullanılır.

### Örnek Kullanım

Aşağıdaki komut, "EskiKlasor" adlı boş bir klasörü siler:

```bash
rmdir EskiKlasor
```
- Not: Bildiğiniz üzere bundan önceki mkdir komutuyla mehmet klasörü oluşturmuştuk. Şimdi onu silicez.
![görsel](/win%20resim/rmdir.png)

### 6.`del` Komutu

- Windows'ta `del` komutu, belirtilen bir dosyayı silmek için kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, "dosya.txt" adlı dosyanın içindieki dosyaları siler.:

```bash
del dosya.txt
```
![görsel](/win%20resim/del.png)
![görsel](/win%20resim/del1.png)

### 7.`copy` Komutu

- Windows'ta `copy` komutu, dosyaları bir yerden başka bir yere kopyalamak için kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, "kaynak.txt" dosyasının içindekileri aynı dizinde "hedef.txt" adıyla kopyalar:

```bash
copy kaynak.txt C:\Users\Username\Documents
```
!Bildiğiniz üzere silme işlemi ile dosya dizininin içini böşaltmıştık.
![görsel](/win%20resim/copy.png)
### 8.`move` Komutu

- Windows'ta `move` komutu, bir dosyayı veya klasörü bir yerden başka bir yere taşımak için kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, "dosya.txt" dosyasını aynı dizinde "yeni_dosya.txt" adıyla taşır:

```bash
move dosya.txt yeni_dosya.txt
```
![görsel](/win%20resim/move.png)
![görsel](/win%20resim/move1.png)

### 9.`tree` Komutu

- Windows'ta `tree` komutu, bir dizinin ve alt dizinlerinin hiyerarşik yapısını görsel olarak gösterir.

### Örnek Kullanım

- Aşağıdaki komut, geçerli dizinin ve alt dizinlerinin ağaç şeklinde bir listesini görüntüler:

```bash
tree
```
![görsel](/win%20resim/tree.png)

### 10.`rename` Komutu

- Windows'ta `rename` komutu, bir dosyanın veya klasörün adını değiştirmek için kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, "eski_dosya.txt" dosyasının adını "yeni_dosya.txt" olarak değiştirir:

```bash
rename eski_dosya.txt yeni_dosya.txt
```
![görsel](/win%20resim/rename.png)
![görsel](/win%20resim/rename1.png)

## Sistem Bilgileri
### 11.`systeminfo` Komutu

- Windows'ta `systeminfo` komutu, bilgisayarınızın sistem bilgilerini detaylı bir şekilde gösterir. Bu komut, işletim sistemi, bellek, ağ yapılandırması ve daha pek çok bilgiyi sağlar.

### Örnek Kullanım

- Aşağıdaki komut, sistem bilgilerinizi görüntüler:

```bash
systeminfo
```
![görsel](/win%20resim/systeminfo.png)
![görsel](/win%20resim/systemindo1.png)

### 12.`ipconfig` Komutu

- Windows'ta `ipconfig` komutu, bilgisayarınızın ağ yapılandırmasını ve IP adresini görüntülemek için kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, bilgisayarınızdaki ağ yapılandırmasını gösterir:

```bash
ipconfig
```
![görsel](/win%20resim/ipconfig.png)

### 13.`ipconfig /all` Komutu

- Windows'ta `ipconfig /all` komutu, bilgisayarınızdaki tüm ağ adaptörlerinin ayrıntılı yapılandırma bilgilerini görüntüler. Bu komut, ağ kartlarının MAC adreslerinden DNS sunucularına kadar pek çok detaylı bilgi sunar.

### Örnek Kullanım

- Aşağıdaki komut, bilgisayarınızdaki tüm ağ adaptörlerinin yapılandırma bilgilerini detaylı şekilde gösterir:

```bash
ipconfig /all
```
![görsel](/win%20resim/ipconfigall.png)
![görsel](/win%20resim/ipconfigall1.png)

### 14. `hostname` Komutu

- Windows'ta `hostname` komutu, bilgisayarınızın ağdaki adını görüntüler. Bu komut, özellikle ağ üzerinde cihaz kimliğini belirlemek için faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, bilgisayarınızın ağda kullandığı ismi görüntüler:

```bash
hostname
```

![görsel](/win%20resim/hostname.png)

### 15.`tasklist` Komutu

- Windows'ta `tasklist` komutu, bilgisayarınızda çalışan tüm işlemlerin (process) bir listesini gösterir. Bu komut, aktif işlemleri izlemek ve yönetmek için kullanışlıdır.

### Örnek Kullanım

- Aşağıdaki komut, bilgisayarınızdaki tüm aktif işlemleri listeleyecektir:

```bash
tasklist
```
![görsel](/win%20resim/tasklist.png)
![görsel](/win%20resim/tasklist%201.png)
![görsel](/win%20resim/tasklist2.png)
![görsel](/win%20resim/tasklist3.png)
### 16.`taskkill` Komutu

- Windows'ta `taskkill` komutu, çalışan bir işlemi sonlandırmak için kullanılır. Bu komut, belirli bir işlem kimliği (PID) veya işlem adı kullanılarak işlem sonlandırma işlemi gerçekleştirir.

### Örnek Kullanım

- Aşağıdaki komut, "notepad.exe" adlı işlemi sonlandırmak için kullanılır.Bu komutu uygulumadan önce bu komuttan önce söylediğimiz `tasklist` komutundan gerekli pid bilgisi alınır. :

```bash
taskkill /pid id_no /f
```
![görsel](/win%20resim/taskkill.png)
![görsel](/win%20resim/taskkill1.png)

### 17.`ver` Komutu

- Windows'ta `ver` komutu, işletim sisteminin sürüm bilgilerini görüntülemek için kullanılır. Bu komut, sistem sürümünü hızlı bir şekilde öğrenmek isteyen kullanıcılar için oldukça pratiktir.

### Örnek Kullanım

- Aşağıdaki komut, işletim sisteminin sürüm numarasını ekranda gösterir:

```bash
ver
```
![görsel](/win%20resim/ver.png)
### 18.`set` Komutu

- Windows'ta `set` komutu, ortam değişkenlerini görüntülemek, ayarlamak veya değiştirmek için kullanılır. Bu komut, özellikle yazılım geliştirme ve sistem yapılandırma işlemlerinde faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, `MY_VARIABLE` adlı bir ortam değişkeni oluşturur ve ona bir değer atar:

```bash
set MY_VARIABLE=Merhaba Dünya
```
### 19.`echo` Komutu

- Windows'ta `echo` komutu, bir metni veya değişkenin değerini komut isteminde görüntülemek için kullanılır. Ayrıca komut dosyaları içinde çıktıyı yönlendirmek için de faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, "Merhaba Dünya"adında dosya oluşturup içine "new" metnini ekrana yazdırır:

```bash
echo Merhaba Dünya > new
```
![görsel](/win%20resim/echo.png)

### 20.## `time` Komutu

- Windows'ta `time` komutu, sistem saatini görüntülemek veya değiştirmek için kullanılır. Bu komut, sistem saatini kontrol etmek veya güncellemek isteyen kullanıcılar için faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, mevcut sistem saatini görüntüler ve değişiklik yapmak isteyip istemediğinizi sorar:

```bash
time
```
![görsel](/win%20resim/time.png)
## Disk ve Depolama İşlemleri
### 21.`diskpart` Komutu

- Windows'ta `diskpart` komutu, disk ve bölümlerle (partitions) çalışmak için kullanılan güçlü bir araçtır. Diskleri yönetmek, bölümleri oluşturmak, silmek veya yeniden boyutlandırmak gibi işlemler için kullanılır. **Dikkat:** Bu komut yanlış kullanıldığında veri kaybına neden olabilir. 

### Örnek Kullanım

- Aşağıdaki örnek, sistemdeki disklerin listesini almak için `diskpart` kullanımı gösterir:

```bash
diskpart
```
- Ardından, diskpart ortamına girdikten sonra şu komutu çalıştırın:
```bash
list disk
```
- Bu komut, sistemdeki tüm diskleri, durumlarını ve boyutlarını görüntüler.
![görsel](/win%20resim/diskpart.png)
### 22.`chkdsk` Komutu

- Windows'ta `chkdsk` (Check Disk) komutu, bir sürücüdeki dosya sistemi ve disk hatalarını taramak ve düzeltmek için kullanılır. Bu komut, disk sağlığını kontrol etmek ve bozuk sektörleri onarmak için faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, `C:` sürücüsünü tarar ve varsa hataları onarır:

```bash
chkdsk C: /f
```
### 23.`format` Komutu

- Windows'ta `format` komutu, bir disk sürücüsünü belirli bir dosya sistemiyle biçimlendirmek için kullanılır. Bu işlem, sürücüdeki tüm verileri siler ve yeniden kullanılabilir hale getirir. **Dikkat:** Bu işlem geri alınamaz, bu nedenle önemli verilerin yedeğini almayı unutmayın.

### Örnek Kullanım

- Aşağıdaki komut, `D:` sürücüsünü NTFS dosya sistemiyle biçimlendirir:

```bash
format D: /FS:NTFS
```
### 24.`vol` Komutu

- Windows'ta `vol` komutu, bir sürücünün birim etiketini (volume label) ve seri numarasını görüntülemek için kullanılır. Bu komut, sürücü bilgilerini hızlıca kontrol etmek için faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, `C:` sürücüsünün birim etiketini ve seri numarasını görüntüler:

```bash
vol C:
```
![görsel](/win%20resim/vol.png)
### 25.`label` Komutu

- Windows'ta `label` komutu, bir sürücünün birim etiketini (volume label) ayarlamak veya değiştirmek için kullanılır. Bu komut, bir sürücüye kolay tanımlanabilir bir ad vermek için faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, `D:` sürücüsüne "VERILER" adını verir:

```bash
label D: VERILER
```
![görsel](/win%20resim/LABEŞ.png)
![görsel](/win%20resim/label1.png)
### 26.`attrib` Komutu

- Windows'ta `attrib` komutu, dosya ve klasörlere ait öznitelikleri (attributes) görüntülemek veya değiştirmek için kullanılır. Bu komut, dosyaları gizlemek, salt okunur yapmak gibi işlemler için kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, `example.txt` dosyasını gizli hale getirir:

```bash
attrib +h example.txt
```
![görsel](/win%20resim/attirib.png)
![görsel](/win%20resim/attirib1.png)

### 27.`diskusage` Komutu

- Windows işletim sisteminde `diskusage` komutu, genellikle disk kullanımını analiz etmek ve görselleştirmek için kullanılan bir komuttur. Bu komut, disk alanını hangi dosya veya klasörlerin kullandığını belirlemenize yardımcı olur. Ancak, Windows’un yerleşik komutları arasında `diskusage` bulunmamaktadır. Bunun yerine, disk kullanım bilgilerini görmek için alternatif komutlar kullanılabilir.

### Alternatif: `dir` Komutu ile Disk Kullanımı

- Örneğin, belirli bir dizinin ne kadar disk alanı kullandığını görmek için **`dir`** komutunu kullanabilirsiniz:

```bash
dir C:\ /s /a
```
![görsel](/win%20resim/diskuage.png)
- Not:
diskusage komutu, genellikle üçüncü taraf araçlarla birlikte gelir ve daha ayrıntılı disk kullanım analizleri sunabilir. Alternatif olarak, PowerShell veya wmic komutları da disk kullanım bilgilerini elde etmek için kullanılabilir.

### 28.`sfc /scannow` Komutu

- Windows işletim sisteminde **`sfc /scannow`** komutu, Sistem Dosyası Denetleyicisi (System File Checker) aracını çalıştırarak, bozulmuş veya eksik olan sistem dosyalarını tarar ve onarır. Bu komut, özellikle sistem hatalarını düzeltmek için oldukça faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, Windows sistem dosyalarındaki bozuklukları tarar ve onarır:

```bash
sfc /scannow
```
![görsel](/win%20resim/sfc.png)

### 29.`defrag` Komutu

- Windows'ta **`defrag`** komutu, sabit disk sürücülerindeki dosya parçalanmalarını düzeltmek için kullanılan bir araçtır. Bu komut, dosyaların daha hızlı ve verimli bir şekilde okunmasını sağlamak amacıyla disk üzerindeki veri bloklarını bir araya getirir.

### Örnek Kullanım

- Aşağıdaki komut, C: sürücüsündeki dosyaları birleştirerek disk birleştirme işlemini başlatır:

```bash
defrag C: /O
```
### 30. ## `fsutil` Komutu

**`fsutil`** komutu, Windows işletim sisteminde dosya sistemiyle ilgili düşük seviyeli işlemleri gerçekleştirmek için kullanılan güçlü bir komuttur. Bu komut, disk bölümleri, diskteki boş alan ve dosya sistemleri gibi öğeler üzerinde işlemler yapmanıza olanak tanır.

### Örnek Kullanım

- Aşağıdaki komut, bir sürücünün boş alan miktarını kontrol etmek için **`fsutil`** komutunu kullanır:

```bash
fsutil volume diskfree C:
```
![görsel](/win%20resim/fsutil.png)


## Ağ ve Bağlantı Komutları
### 31. `ping` Komutu

- **`ping`** komutu, bir ağ bağlantısının çalışıp çalışmadığını test etmek ve hedef bir cihaz ile iletişim kurma hızını ölçmek için kullanılan basit ama etkili bir ağ aracıdır. Bu komut, belirli bir IP adresine veya alan adına ICMP Echo Request paketleri gönderir ve yanıt sürelerini ölçer.

### Örnek Kullanım

- Aşağıdaki komut, **Google'ın sunucusuna** ping gönderir ve bağlantıyı test eder:

```bash
ping www.google.com
```
![görsel](/win%20resim/ping.png)

### 32.`tracert` Komutu

- **`tracert`** komutu, bir hedefe ulaşana kadar geçen ağ yolunu ve her bir ara noktadaki (hop) gecikme sürelerini gösteren bir ağ aracıdır. Bu komut, bir IP adresi veya alan adına giden paketlerin geçtikleri yönlendiricileri (routers) ve her bir aşamadaki yanıt sürelerini listeler.

### Örnek Kullanım

- Aşağıdaki komut, **Google'ın sunucusuna** giden ağ yolunu izler:

```bash
tracert www.google.com
```
![görsel](/win%20resim/tracert.png)

### 33.`netstat` Komutu

- **`netstat`** (Network Statistics), bilgisayarınızdaki ağ bağlantıları ve ağ trafiği hakkında bilgi sağlayan bir komuttur. Bu komut, aktif ağ bağlantılarını, dinleme portlarını ve bağlı olan uzak sistemlerle olan bağlantıları gösterir.

### Örnek Kullanım

- Aşağıdaki komut, aktif ağ bağlantılarınızı ve bunların durumlarını listeler:

```bash
netstat
```
![görsel](/win%20resim/netstat.png)
### 34.`arp` Komutu

- **`arp`** komutu, **Address Resolution Protocol (ARP)** tablosundaki bilgileri görüntülemenizi ve yönetmenizi sağlar. ARP, IP adreslerini fiziksel (MAC) adreslerine çözümleyen bir protokoldür. Bu komut, ağınızdaki cihazların MAC adresleri ile IP adreslerini ilişkilendirir.

### Örnek Kullanım

- Aşağıdaki komut, ARP tablosunu görüntüler:

```bash
arp -a
```
![görsel](/win%20resim/arp.png)

### 35.`nslookup` Komutu

- **`nslookup`** (Name Server Lookup), DNS (Domain Name System) sorgulamalarını yaparak, alan adı (domain) ile ilgili bilgileri ve IP adreslerini öğrenmenizi sağlar. Bu komut, özellikle ağ bağlantı sorunlarını gidermek için kullanılır ve DNS sunucusunun nasıl yanıt verdiğini kontrol etmek için yararlıdır.

### Örnek Kullanım

- Aşağıdaki komut, `example.com` alan adının IP adreslerini sorgular:

```bash
nslookup example.com
```
![görsel](/win%20resim/nslookup.png)

### 36.`netsh` Komutu

- **`netsh`** (Network Shell), Windows işletim sisteminde ağ ayarlarını yönetmek için kullanılan güçlü bir komuttur. Bu komut, ağ yapılandırmalarını görüntülemenizi, değiştirmenizi ve sıfırlamanızı sağlar. Özellikle ağ sorunlarını çözmek, ağ bağlantılarını yapılandırmak ve ağ cihazlarını yönetmek için yaygın olarak kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, bilgisayarınızdaki ağ yapılandırmalarını görüntüler:

```bash
netsh interface ip show config
```
- interface ip show config: Bu parametre, ağ bağdaştırıcıları için IP yapılandırmalarını görüntüler. IP adresi, alt ağ maskesi ve varsayılan ağ geçidi gibi bilgileri içerir.

![görsel](/win%20resim/netsh.png)

### 37.`telnet` Komutu

- **`telnet`**, uzak bir cihazla terminal tabanlı bir bağlantı kurmanıza olanak tanır. Genellikle ağ bağlantılarını test etmek veya uzak sunucularda oturum açmak için kullanılır. Ancak, modern güvenlik uygulamaları nedeniyle, Telnet'in yerine daha güvenli bağlantı protokolleri (örneğin SSH) tercih edilmektedir. Yine de bazı eski sistemlerde veya ağ bağlantılarını test etmek için Telnet hala kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, `example.com` domainine, 80 numaralı port üzerinden Telnet bağlantısı başlatır (HTTP için yaygın port):

```bash
telnet example.com 80
```
### 38.`ftp` Komutu

- **`ftp`**, bir dosya aktarım protokolüdür ve uzak bir sunucuya bağlanarak dosya yükleme, indirme, listeleme gibi işlemleri gerçekleştirmenizi sağlar. Bu komut, özellikle dosya aktarımında kullanılan temel araçlardan biridir. Windows üzerinde, `ftp` komutu, terminal veya komut istemcisi üzerinden erişilebilir.

### Örnek Kullanım

- Aşağıdaki komut, bir FTP sunucusuna bağlanmanızı sağlar:

```bash
ftp ftp.example.com
```
### 39.`pathping` Komutu

- **`pathping`**, ağ bağlantısı sorunlarını teşhis etmek için kullanılan bir komuttur. Bu komut, ağda bir hedefe ulaşana kadar geçen tüm yönlendiricileri (router) takip eder ve her bir yönlendiricinin performansını analiz eder. Hem **`ping`** komutunun hem de **`tracert`** komutunun özelliklerini birleştirerek, ağ bağlantısı hakkında daha detaylı bilgi sağlar.

### Örnek Kullanım

- Aşağıdaki komut, `example.com` adresine giden yol boyunca ağ bağlantısını analiz eder:

```bash
pathping example.com
```
### 40.`route` Komutu

- **`route`**, Windows işletim sisteminde ağ yönlendirme tablosunu görüntülemek, eklemek veya değiştirmek için kullanılan bir komuttur. Bu komut, ağdaki veri iletiminin hangi yollarla gerçekleştirileceğini belirleyen yönlendirme tablosunu yönetmek için kullanılır. Özellikle ağ yapılandırmalarını test etmek ve sorunları gidermek için faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, mevcut yönlendirme tablosunu görüntüler:

```bash
route print
```
![görsel](/win%20resim/route.png)

## Gelişmiş Sistem İşlemleri
### 41.`shutdown` Komutu

- **`shutdown`**, Windows işletim sisteminde bilgisayarı kapatmak, yeniden başlatmak veya belirli bir süre sonra otomatik olarak kapatılmasını sağlamak için kullanılan bir komuttur. Bu komut, sistem yöneticilerinin ve kullanıcılarının bilgisayarlarını yönetmesini kolaylaştırır.

### Örnek Kullanım

- Aşağıdaki komut, bilgisayarı hemen kapatır:

```bash
shutdown /s /f /t 0
```
### 42. ## `cls` Komutu

- **`cls`**, Windows komut satırında ekranı temizlemek için kullanılan basit bir komuttur. Bu komut, terminaldeki mevcut çıktıyı siler ve ekranı temizler, böylece daha düzenli bir çalışma ortamı sağlar. Özellikle uzun bir işlem geçmişi veya çok sayıda komut sonucu ekranı karıştırıyorsa, **`cls`** komutu çok faydalıdır.

### Örnek Kullanım

- Aşağıdaki komut, komut satırındaki tüm çıktıyı temizler:

```bash
cls
```
### 43. `pause` Komutu

- **`pause`**, Windows komut satırında çalışan bir komuttur ve komut satırındaki işlemin duraklatılmasını sağlar. Bu komut, kullanıcıya bir tuşa basarak devam etme imkanı tanır, genellikle toplu iş dosyalarında veya komut dizilerinde işlem adımlarının kontrol edilmesini sağlamak için kullanılır.

### Örnek Kullanım
 
 - Aşağıdaki komut, işlemin duraklatılmasını ve kullanıcıdan bir tuşa basarak devam etmesini sağlar:

```bash
pause
```
### 44. ## `exit` Komutu

- **`exit`**, Windows komut satırını veya PowerShell oturumunu sonlandırmak için kullanılan bir komuttur. Bu komut, aktif oturumun kapanmasını sağlar ve genellikle script veya işlem tamamlandıktan sonra terminalin kapanması için kullanılır.

### Örnek Kullanım

- Aşağıdaki komut, aktif komut satırı oturumunu kapatır:

```bash
exit
```
### 45.`assoc` Komutu

- **`assoc`**, Windows komut satırında dosya uzantıları ile ilişkilendirilmiş programları yönetmek için kullanılan bir komuttur. Bu komut, bir dosya türü ile ilişkilendirilmiş programı görüntülemenize veya değiştirmeye olanak tanır.

### Örnek Kullanım

- Bir dosya uzantısının hangi programla ilişkilendirildiğini görmek için şu komutu kullanabilirsiniz:

```bash
assoc .txt
```
### 46.`fc` Komutu

- **`fc`**, Windows komut satırında iki dosya arasındaki farkları karşılaştırmak için kullanılan bir komuttur. Bu komut, metin dosyalarındaki değişiklikleri hızlıca tespit etmek için idealdir.

### Örnek Kullanım

- İki dosya arasındaki farkları görmek için şu komutu kullanabilirsiniz:

```bash
fc file1.txt file2.txt
```
### 47.`powercfg` Komutu

- **`powercfg`**, Windows işletim sistemindeki güç yönetimi ayarlarını yapılandırmak ve sistemin enerji tüketimini optimize etmek için kullanılan güçlü bir komuttur. Bu komutla, güç planlarını görüntüleyebilir, değiştirebilir ve sistemin güç kullanımını daha verimli hale getirebilirsiniz.

### Örnek Kullanım

- Mevcut güç planlarını listelemek için şu komutu kullanabilirsiniz:

```bash
powercfg /list
```
![görsel](/win%20resim/powercfg.png)

### 48.`schtasks` Komutu

**`schtasks`**, Windows'ta zamanlanmış görevler oluşturmak ve yönetmek için kullanılan güçlü bir komuttur. Bu komut, belirli bir zaman diliminde veya belirli bir koşul altında otomatik olarak çalışacak görevler ayarlamanızı sağlar.

### Örnek Kullanım

Bir görev oluşturmak için şu komutu kullanabilirsiniz:

```bash
schtasks /create /tn "MyTask" /tr "C:\Path\To\YourProgram.exe" /sc daily /st 09:00
```
- Bu komut, MyTask adında bir zamanlanmış görev oluşturur ve her gün sabah saat 09:00'da YourProgram.exe dosyasını çalıştırır.
### 49. `reg` Komutu

**`reg`** komutu, Windows işletim sisteminde kayıt defteri (registry) üzerinde çeşitli işlemler yapmanızı sağlar. Bu komut ile kayıt defterine anahtar ekleyebilir, silebilir, güncelleyebilir veya mevcut anahtarları görüntüleyebilirsiniz. Windows'un yapılandırmalarını değiştirmek ve yönetmek için oldukça kullanışlıdır.

### Örnek Kullanım

Bir kayıt defteri anahtarını listelemek için şu komutu kullanabilirsiniz:

```bash
reg query HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion
```
- Bu komut, belirtilen kayıt defteri anahtarındaki tüm değerleri ve alt anahtarları görüntüler.

![görsel](/win%20resim/reg.png)

### 50. ## `wmic` Komutu

**`wmic`**, Windows Management Instrumentation Command-line (WMIC) aracıdır ve Windows işletim sistemindeki sistem bilgilerini yönetmek ve sorgulamak için kullanılan güçlü bir komuttur. Bu komut ile donanım, yazılım, ağ ayarları ve sistem bileşenleri hakkında derinlemesine bilgi alabilirsiniz.

### Örnek Kullanım

Bilgisayarınızın sistem bilgilerini görüntülemek için şu komutu kullanabilirsiniz:

```bash
wmic os get caption, version, architecture
```
## Sonuç

- Windows işletim sistemindeki **komut satırı** araçları, yönetim ve sistem yapılandırmalarını verimli bir şekilde gerçekleştirmek için güçlü birer araçtır. **`wmic`**, **`reg`**, **`ping`** gibi komutlar, sistem bilgilerini sorgulamak, donanım ve yazılım yönetimini sağlamak, ağ bağlantılarını kontrol etmek ve daha birçok işlemi hızlı bir şekilde gerçekleştirmek için büyük kolaylık sağlar.

- Bu araçların doğru bir şekilde kullanılması, sistem yönetimini basitleştirir ve zaman kazandırır. Her bir komut, Windows ortamında profesyonel düzeyde işlem yapabilmenizi sağlar, böylece bilgisayarınızın performansını en üst düzeye çıkarabilir ve sistem hatalarını anında tespit edebilirsiniz.

- Komut satırını etkili kullanmak, sistem yöneticiliği ve günlük bilgisayar kullanımı için oldukça faydalıdır. Bu araçların sağladığı esneklik ile işletim sistemi üzerinde daha fazla kontrol sahibi olabilir, işlerinizin verimliliğini artırabilirsiniz.

- Haydi, şimdi siz de bu komutları keşfedin ve Windows işletim sisteminizin gizli güçlerini kullanmaya başlayın!
# Okuduğunuz için teşekkürler. 
#### Hazırlayan: Mehmet Kocabıyık





































