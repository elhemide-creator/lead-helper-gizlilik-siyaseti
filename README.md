# lead-helper-gizlilik-siyaseti
Bəli, vebsaytınız olmadıqda gizlilik siyasətini necə hazırlayıb yayımlayacağınızı addım-addım izah edirəm. Bu proses üçün **GitHub**-dan istifadə edəcəyik, çünki bu platforma sənədləri pulsuz saxlamağa və ictimaiyyətə açmağa imkan verir.

-----

### **Gizlilik Siyasətini GitHub-da Hazırlamaq**

#### **Addım 1: GitHub Hesabı Yaratmaq**

Əgər GitHub hesabınız yoxdursa, `https://github.com/` ünvanına gedib pulsuz bir hesab yaradın. Bu platforma proqramlaşdırma layihələrini saxlamaq üçün istifadə edilir, lakin hər cür sənəd üçün də uyğundur.

#### **Addım 2: Yeni Bir Repository Yaratmaq**

1.  Hesabınıza daxil olun.
2.  Sağ yuxarı küncdəki "+" düyməsinə klikləyin və **"New repository"** (Yeni repository) seçin.
3.  Repository üçün bir ad yazın. Ad uzantınızın adı ilə bağlı ola bilər (məsələn: `lead-helper-gizlilik-siyaseti`).
4.  Repository-ni **"Public"** (İctimai) olaraq seçin. Bu vacibdir, çünki gizlilik siyasəti hər kəs tərəfindən görünməlidir.
5.  **"Add a README file"** (README faylı əlavə et) bəndini işarələyin.
6.  **"Create repository"** (Repository yarat) düyməsinə klikləyin.

#### **Addım 3: Gizlilik Siyasəti Faylını Yaratmaq**

1.  Yaratdığınız repository-yə daxil olun.
2.  **"Add file"** (Fayl əlavə et) düyməsinə klikləyin və **"Create new file"** (Yeni fayl yarat) seçin.
3.  Fayl adı olaraq `PRIVACY_POLICY.md` yazın. `.md` uzantısı Markdown faylı deməkdir və formatlamanı asanlaşdırır.
4.  Aşağıdakı məzmunu faylın içinə köçürün və **uzantınızın adını** uyğun olaraq dəyişin:

<!-- end list -->

```
# [Uzantınızın Adı] Gizlilik Siyasəti

Bu gizlilik siyasəti, [Uzantınızın Adı] brauzer uzantısının istifadəçi məlumatlarını necə topladığını, istifadə etdiyini və qoruduğunu izah edir.

**Toplanan Məlumatlar**

Uzantı aşağıdakı məlumatları toplayır və istifadə edir:
* **İstifadəçi fəaliyyəti:** Paneldəki düymələrə klikləmə, mətn sahələrinə məlumat daxil etmə və paneli sürüşdürmə kimi fəaliyyətlər. Bu məlumatlar uzantının funksiyalarını yerinə yetirmək üçün daxili olaraq istifadə olunur.
* **Veb-sayt məzmunu:** Uzantı, CRM səhifəsindəki qeydləri yeniləmək üçün mətn sahəsinə giriş edir.

**Məlumatların İstifadəsi**

Toplanan məlumatlar yalnız aşağıdakı məqsədlər üçün istifadə olunur:
* Uzantının əsas funksiyalarını təmin etmək.
* İstifadəçi parametrlərini (ad, qeyd qutuları, şablonlar, mövzu seçimləri və s.) yadda saxlamaq.

**Məlumatların Saxlanılması və Təhlükəsizliyi**

* Bütün istifadəçi məlumatları **yalnızca sizin yerli brauzerinizdə saxlanılır.** Heç bir məlumat bizim serverlərimizə və ya hər hansı üçüncü tərəfə göndərilmir, satılmır və ya paylaşılmır.
* Bu uzantı internetə çıxış tələb etmir.

**Məlumatların Paylaşılması**

Uzantı heç bir istifadəçi məlumatını üçüncü tərəflərlə paylaşmır.

**Əlaqə**

Gizlilik siyasəti ilə bağlı hər hansı sualınız varsa, [email adresinizi] ünvanına yaza bilərsiniz.

---

#### **Addım 4: Faylı Yadda Saxlamaq və URL-i Əldə Etmək**
1. Məzmunu yapışdırdıqdan sonra, aşağıdakı **"Commit new file"** (Yeni faylı təsdiqlə) yaşıl düyməsinə klikləyin.
2. Faylı yadda saxladıqdan sonra, repository səhifəsindəki `PRIVACY_POLICY.md` faylının adını klikləyin.
3. Brauzerinizin ünvan çubuğundakı URL-i kopyalayın. Məsələn, URL belə görünəcək: `https://github.com/sizinprofiliniz/uzanti-adi/blob/main/PRIVACY_POLICY.md`

Bu URL-i **"Gizlilik politikası URL'si"** sahəsinə yapışdıra bilərsiniz. Bu, uzantınızın heç bir məlumatı xarici serverlərə göndərmədiyini açıq şəkildə ifadə etdiyi üçün tələblərə tam cavab verir.
```
