# 📘 Turkcell ASP.NET Core MVC Eğitim Projesi

Bu GitHub reposu, [Turkcell Geleceği Yazanlar](https://gelecegiyazanlar.turkcell.com.tr/egitimler/aspnet-core-mvc) platformundaki **ASP.NET Core MVC Eğitimi** süresince geliştirilmiş tüm örnekleri ve uygulamaları içermektedir. Eğitim boyunca temel web geliştirme becerileri ASP.NET Core MVC çatısı altında ele alınmış ve gerçek dünya senaryolarıyla desteklenmiştir.

## 🎯 Proje Amacı

Bu projenin temel amacı, ASP.NET Core MVC mimarisini öğrenmek isteyenler için hem teorik bilgiyi hem de pratik uygulamaları bir araya getirmektir. MVC mimarisinin temel yapı taşları olan **Model**, **View**, **Controller** kavramları üzerinde durularak; modern web uygulamalarının nasıl inşa edildiği adım adım gösterilmektedir.

## 🧩 Eğitimde İşlenen Konular

Her modülde ayrı bir uygulama veya fonksiyonel bir bileşen geliştirilmiştir. Aşağıda öne çıkan başlıkları bulabilirsiniz:

- ASP.NET Core MVC’ye Giriş
- MVC Pattern: Model, View, Controller Yapısı
- Routing ve Endpoints Kullanımı
- Razor Syntax ve Razor Pages
- Strongly Typed View Kullanımı
- ViewModel ile Veri Taşımak
- Formlar ve Form İşlemleri (GET / POST)
- Veri Doğrulama (Validation) ve Fluent Validation
- CRUD (Create, Read, Update, Delete) İşlemleri
- Entity Framework Core ile Veritabanı Entegrasyonu
- Layout, Partial View, ViewComponent
- TempData, ViewBag, ViewData Kullanımı
- Session Yönetimi
- LINQ ile Veri Sorgulama
- Sayfalama (Paging) ve Filtreleme

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|----------|----------|
| **ASP.NET Core MVC** | Web uygulaması geliştirme çatısı |
| **Entity Framework Core** | ORM (Object-Relational Mapping) |
| **Razor** | Sayfa tasarımı için dinamik HTML |
| **SQL Server (LocalDB)** | Veritabanı yönetimi |
| **Visual Studio 2022** | Geliştirme ortamı |
| **.NET 8** | Uygulamanın hedef framework'ü |

## 🔧 Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

### 1. Reponun Klonlanması

git clone https://github.com/mrvekratl/Turkcell-AspNetCoreApp.git

cd Turkcell-AspNetCoreApp

### 2. Visual Studio ile Açın

Projeyi Visual Studio 2022 ile açın.

Gerekirse .NET 8 SDK’sının sisteminizde kurulu olduğundan emin olun.

### 3. Veritabanı Bağlantısı

appsettings.json içindeki ConnectionString satırını kendi SQL Server ortamınıza göre güncelleyin:

"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\MSSQLLocalDB;Database=TurkcellMvcDb;Trusted_Connection=True;"
}

### 4. Migration ve Veritabanı Oluşturma

Visual Studio'da Package Manager Console'u açın ve aşağıdaki komutu çalıştırarak veritabanını oluşturun:

Update-Database

### 5. Uygulamayı Çalıştırma

Projeyi başlatmak için Ctrl + F5 tuşlarına basabilir veya debug modda başlatabilirsiniz.

## 📂 Proje Yapısı

| Klasör / Dosya        | Açıklama                                       |
|-----------------------|------------------------------------------------|
| `Controllers/`        | MVC Controller dosyaları                       |
| `Models/`             | Veri modelleri                                 |
| `Views/`              | Razor view dosyaları                           |
| `ViewModels/`         | UI için özel ViewModel sınıfları               |
| `Data/`               | Veritabanı bağlamı ve konfigürasyonları        |
| `wwwroot/`            | Statik dosyalar (CSS, JS, görseller)           |
| `appsettings.json`    | Uygulama ayarları ve connection string         |
| `Program.cs`          | Giriş noktası ve middleware konfigürasyonu     |

## ✅ Öğrenilenler

Bu proje sayesinde aşağıdaki beceriler kazanılmıştır:

Web tabanlı yazılım projelerinde MVC yapısını uygulayabilme

Veri katmanı ile kullanıcı arayüzü arasında veri taşıma teknikleri

Modern form işleme yöntemleri

Katmanlı mimari ve best-practice uygulamaları

Temiz kod ve SOLID prensiplerine uygun geliştirme

Geliştirici dostu hata yönetimi ve kullanıcı deneyimi

## 📌 Notlar

Proje eğitsel amaçlıdır, gerçek dünya uygulaması olarak geliştirilmemiştir.

Her modül, farklı bir ASP.NET MVC özelliğini öğretmeye yönelik oluşturulmuştur.

Kodlar ve yapılar sade ve anlaşılır bir şekilde tasarlanmıştır.

## 🙋‍♀️ Geliştirici

Merve Kıratlı

📧 İletişim: GitHub Profilim

🎓 Eğitim: Siliconmade Academy - Backend Developer Programı

