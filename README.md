# Foundry FundMe

Foundry FundMe, Foundry kullanılarak geliştirilmiş merkeziyetsiz bir kitle fonlama uygulamasıdır. Güvenli ve şeffaf bir şekilde fon toplamak için akıllı sözleşmeleri kullanır.

## Özellikler

- **Merkeziyetsiz Fonlama**: Blockchain teknolojisini kullanarak güvenli ve şeffaf bir şekilde fon toplayın.
- **Akıllı Sözleşmeler**: Solidity ile geliştirilmiş ve Ethereum'un Sepolia test ağında dağıtılmıştır.
- **Foundry Entegrasyonu**: Test, dağıtım ve geliştirme için Foundry kullanılarak inşa edilmiştir.

## Kurulum

1. **Depoyu Klonlayın**

   ```bash
   git clone https://github.com/admults25/Foundry-fundMe.git
   cd Foundry-fundMe
2.  **Gereklilikleri Yükleyin**
    Foundry'nin yüklü olduğundan emin olun
    ``` forge install ```
3.  **Gerekli Ortam Değişkenlerini Yükleyin**
   Gerekli ortam değişkenleri ile .env dosyasını oluşturup düzenleyin örnek :
    ```SEPOLIA_RPC_URL=your_sepolia_rpc_url```
     ```PRIVATE_KEY=your_private_key ```
    
## Kullanım

1. **Testleri çalıştırın**
``` Forge test ```
2. **Akıllı Sözleşmeleri Dağıtın**
```forge deploy --network sepolia ```

   
