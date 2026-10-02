# 🐆 Jaguar Stealth

Windows için ultra hızlı yerel DPI engeli aşma ve DNS-over-HTTPS (DoH) aracı.  
Harici VPN gerektirmez, paketleri yerel düzeyde parçalayarak hız kaybı ve ping artışı olmadan sansürleri ve erişim engellerini aşar.

---

### 📥 İndir

En güncel sürümü (Portable veya Setup) doğrudan GitHub Releases sayfasından edinebilirsiniz:

🚀 **[En Güncel Sürümü İndir (Releases)](https://github.com/Elbahram0/Jaguar-Stealth/releases/latest)**

> ⚠️ **Not:** Ağ soketleri ve yerel yönlendirmeleri yapılandırabilmesi için uygulamanın Yönetici İzni (Run as Administrator) ile çalıştırılması gerekir.

---

### 🚀 Geliştirme ve Derleme

```powershell
# Geliştirme modu:
cd ui
npm install
npm run dev

# Tek tıkla Portable ve Setup .exe paketleme:
.\build.ps1
```

---

### 🛠 Mimari

- **`core/`**: Go ile yazılmış yüksek performanslı yerel servis (TCP ClientHello SNI parçalama, DoH paralel DNS sorgulama, yerel hosts yönlendirme).
- **`ui/`**: Electron + React + TailwindCSS ile geliştirilmiş modern masaüstü ve sistem tepsisi (System Tray) arayüzü.

---

### 👤 İletişim

- **Telegram:** [@El_bahram](https://t.me/El_bahram)
- **YouTube:** [@orucdemiros](https://youtube.com/@orucdemiros)
- **GitHub:** [Elbahram0](https://github.com/Elbahram0)
