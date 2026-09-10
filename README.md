# 🐆 Jaguar Stealth

Windows için ultra hızlı yerel DPI engeli aşma ve DNS-over-HTTPS (DoH) aracı.  
Harici VPN gerektirmez, paketleri yerel kernel düzeyinde (WinDivert) parçalayarak hız kaybı olmadan sansürleri aşar.

---

### 📥 Doğrudan İndir

Aşağıdaki butonlara tıklayarak doğrudan indirebilirsiniz:

- 🚀 **[Portable Sürümü İndir (.exe)](https://github.com/Elbahram0/Jaguar-Stealth/releases/latest/download/Jaguar-Stealth-Portable-1.0.0.exe)** *(Kurulum gerektirmez, doğrudan çalışır)*
- 📦 **[Setup Kurulum Sürümünü İndir (.exe)](https://github.com/Elbahram0/Jaguar-Stealth/releases/latest/download/Jaguar-Stealth-Setup-1.0.0.exe)** *(Masaüstü kısayollu yükleyici)*

> ⚠️ **Not:** WinDivert kernel paket sürücüsü gerektirdiği için uygulama açılırken Yönetici İzni (UAC) isteyecektir.

---

### 🚀 Geliştirme ve Derleme

```powershell
# Geliştirme modu:
cd ui
npm install
npm run dev

# Tek tıkla Portable ve Setup .exe paketleme:
.\build.ps1
