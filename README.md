# Montra App

Bu proje, kullanıcıların gelir, gider ve transfer işlemlerini takip edebilecekleri, kamera ile fiş bilgilerini otomatik olarak işleyebilecekleri ve harcamalarını grafiklerle analiz edebilecekleri bir mobil uygulamadır. React Native kullanılarak geliştirilmiştir.

### Önkoşullar

Projenin çalışması için aşağıdaki yazılımların yüklü olması gerekmektedir:

- Node.js (v14.x veya daha üstü)
- npm veya yarn
- React Native CLI
- Android Studio (Android için)
- Xcode (iOS için)

### Özellikler

- Gelir, Gider ve Transfer Girdileri: Kullanıcılar üç farklı tipte harcama girişi yapabilirler.
- Otomatik Fiş İşleme: Kameradan çekilen fişlerin bilgileri otomatik olarak harcamalara eklenir.
- Grafik Analizi: Kullanıcılar harcamalarını günlük, haftalık ve aylık olarak grafik üzerinden izleyebilir ve yorumlayabilirler.
- Budget Modülü: Kullanıcılar belirledikleri bütçeyi takip edebilir ve harcamalarına göre öneriler alabilirler.


### Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin.

1. Bu projeyi yerel makinenize klonlayın:

    ```bash
    git clone https://github.com/BATUHAN-ANKARA/montra.git
    ```

2. Proje dizinine gidin:

    ```bash
    cd example
    ```

3. Gerekli bağımlılıkları yükleyin:

    ```bash
    npm install
    ```

   veya

    ```bash
    yarn install
    ```

4. iOS için Çalıştırın

    ios klasörüne gidin

    ```bash
    cd ios
    ```
    pod indirmelerini yapın

    ```bash
    pod install
    ```
    ana dizine geri dönün

    ```bash
    cd ..
    ```
    iOS için çalıştırma komutu

    ```bash
    npx react-native run-ios
    ```

5. Android için Çalıştırın

     ```bash
    npx react-native run-android
    ```


### Kullanım

#### Gelir, Gider ve Transfer Girişi
- Gelir Girişi: Ana ekrandan gelir ekleme butonuna basarak gelirlerinizi girebilirsiniz.
- Gider Girişi: Ana ekrandan gider ekleme butonuna basarak giderlerinizi girebilirsiniz.
- Transfer Girişi: Ana ekrandan transfer ekleme butonuna basarak transferlerinizi girebilirsiniz.
- Otomatik Fiş İşleme: Kamera ikonuna tıklayarak fişinizi çekin. Uygulama fişteki bilgileri otomatik olarak tanıyıp harcama olarak ekleyecektir.
- Grafik Analizi Ana ekrandan grafik ikonuna tıklayarak harcamalarınızı günlük, haftalık ve aylık olarak analiz edebilirsiniz.
- Budget Modülü: Budget modülüne girerek belirlediğiniz bütçeyi takip edebilir ve öneriler alabilirsiniz.

## Katkıda Bulunma

1. Fork yapın (https://github.com/BATUHAN-ANKARA/Montra/fork)
2. Yeni bir dal oluşturun (`git checkout -b feature/xyz`)
3. Değişikliklerinizi yapın
4. Değişikliklerinizi kaydedin (`git commit -am 'Add some xyz'`)
5. Dalınıza itme yapın (`git push origin feature/xyz`)
6. Bir Pull Request açın

## İletişim
Herhangi bir soru veya öneriniz için bthnankara@gmail.com adresinden iletişime geçebilirsiniz.
