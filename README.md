# Açıklanabilir Yapay Zekâ (XAI): Güvenilirlik, Algoritmik Zayıflıklar ve Değerlendirme Çerçeveleri

## 1. Depo hakkında

Bu GitHub deposu, **Açıklanabilir Yapay Zekâ (Explainable Artificial Intelligence – XAI)** alanındaki sistematik literatür incelemesine eşlik eden, araştırmacı tarafından düzenlenmiş ve kodlanmış çalışma veri tabanını sunmaktadır.

Ana nicel analiz havuzu, **2016–2026 yılları arasında yayımlanan 298 çalışmadan** oluşmaktadır. Excel dosyası, incelemeye dâhil edilen çalışmaların bibliyografik ve kodlama bilgilerini ve bu çalışmalar üzerinden oluşturulan betimsel dağılımları içerir.

> **Önemli açıklama:** Depodaki Excel dosyası, sistematik inceleme için düzenlenmiş ve kodlanmış nihai veri tabanıdır. Scopus, Web of Science, IEEE Xplore veya ACM Digital Library üzerinden doğrudan indirilen ham bibliyografik dışa aktarma dosyaları değildir. Ham dışa aktarma dosyaları şu anda mevcut değildir; bu nedenle depoda bu dosyaların sunulduğu iddia edilmemektedir.

## 2. Depodaki dosyalar

| Dosya / çalışma sayfası | Açıklama |
|---|---|
| `XAI_SLR_Database_298_2016_2026.xlsx` | 298 çalışmayı içeren, kodlanmış ana veri tabanı ve betimsel özetler. |
| `SLR 2016-2026` çalışma sayfası | Sistematik incelemeye dâhil edilen çalışmaların kayıtları ve kodlama alanları. |
| `Summary` çalışma sayfası | Yayın yılı, baskın XAI yöntemi kategorisi, açıklama zamanlaması, uygulama alanı ve açıklama kapsamına ilişkin frekanslar. |

**Dosya adı notu:** Excel dosyasını GitHub'a yüklerken yukarıdaki dosya adını aynen kullanın. Depodaki gerçek dosya adı ile bu README'de ve makalede belirtilen dosya adı birbiriyle aynı olmalıdır.

## 3. İncelemenin kapsamı

Ana sistematik inceleme ve nicel analizler, 2016–2026 döneminde yayımlanan ve belirlenen dâhil etme ölçütlerini karşılayan 298 çalışmaya dayanmaktadır.

2016 öncesinde yayımlanan çalışmalar, XAI alanının tarihsel gelişimini ve yöntemsel temellerini açıklamak amacıyla arka plan kaynakları olarak kullanılabilir; ancak 298 çalışmadan oluşan ana nicel analiz havuzuna dâhil değildir.

2026 yılı, incelemede belirtilen arama/güncelleme döneminin bir parçasıdır. Bu nedenle 2026 sayısı, yılın tamamına ait eksiksiz yayın sayısı olarak yorumlanmamalıdır.

## 4. Veri alanları ve kodlama yapısı

`SLR 2016-2026` çalışma sayfasındaki alanlar, veri tabanında yer aldıkları biçimiyle aşağıda açıklanmıştır.

| Alan | Açıklama |
|---|---|
| `ID` | Veri tabanındaki çalışma kimliği. |
| `Author(s)` | Kaydedilen yazar veya kaynak bilgisi. |
| `Year` | Yayın yılı. |
| `Title` | Çalışmanın başlığı. |
| `Publication / Source` | Dergi, konferans, bildiri kitabı veya diğer yayın kaynağı. |
| `Model Type` | Çalışmada kaydedilen genel model veya çalışma türü. |
| `XAI Method` | Çalışmada ele alınan XAI yöntemi veya tekniği. |
| `Coding Category (Dominant Type)` | Özet analizinde kullanılan baskın XAI kategorisi. |
| `Explanation Scope` | Açıklamanın global, local veya her ikisi olarak kodlanması. |
| `Explanation Timing` | Açıklamanın post-hoc veya intrinsic olarak kodlanması. |
| `Application Domain` | Çalışma için belirlenen temel uygulama alanı. |
| `Evaluation Metric` | Çalışmada kaydedilen değerlendirme metriği veya nitel değerlendirme yaklaşımı. |

Alan adları Excel dosyasında İngilizce tutulmuştur; bu tabloda Türkçe açıklamaları verilmiştir.

## 5. Veri tabanındaki betimsel dağılımlar

Aşağıdaki sayılar, mevcut Excel dosyasının `Summary` çalışma sayfasındaki özetleri yansıtmaktadır. Veri tabanında değişiklik yapılırsa özetlerin yeniden hesaplanması gerekir.

### 5.1. Yayın yılı

| Yıl | Çalışma sayısı |
|---:|---:|
| 2016 | 13 |
| 2017 | 25 |
| 2018 | 52 |
| 2019 | 71 |
| 2020 | 68 |
| 2021 | 38 |
| 2022 | 1 |
| 2023 | 3 |
| 2024 | 13 |
| 2025 | 9 |
| 2026 | 5 |
| **Toplam** | **298** |

### 5.2. Baskın XAI yöntemi kategorisi

| Kategori | Çalışma sayısı |
|---|---:|
| Özellik katkısına dayalı açıklamalar (Feature Attribution) | 118 |
| İçsel / beyaz-kutu yöntemler (Intrinsic White-box) | 85 |
| Kural tabanlı açıklamalar (Rule-based Explanations) | 40 |
| Görsel belirginlik / ısı haritası yöntemleri (Visual Saliency / Heatmap) | 34 |
| Örnek / prototip tabanlı yöntemler (Example / Prototype-based) | 14 |
| Kavram tabanlı yöntemler (Concept-based) | 7 |
| **Toplam** | **298** |

### 5.3. Açıklama zamanlaması

| Zamanlama | Çalışma sayısı |
|---|---:|
| Sonradan açıklama (Post-hoc) | 198 |
| İçsel açıklanabilirlik (Intrinsic) | 100 |
| **Toplam** | **298** |

### 5.4. Uygulama alanı

| Uygulama alanı | Çalışma sayısı |
|---|---:|
| Genel / kıyaslama (General / Benchmark) | 111 |
| Bilgisayarlı görü ve otonom sistemler | 59 |
| Sağlık | 51 |
| Siber güvenlik ve Nesnelerin İnterneti (IoT) | 28 |
| Finans ve kredi riski | 27 |
| Doğal dil işleme ve öneri sistemleri | 22 |
| **Toplam** | **298** |

### 5.5. Açıklama kapsamı

| Kapsam | Sayı |
|---|---:|
| Global (etkin sayım) | 174 |
| Local (etkin sayım) | 139 |
| Hem Global hem Local olarak kodlananlar | 15 |

**Yorumlama notu:** Global ve Local için verilen etkin sayımlar birbirini dışlayan kategoriler değildir. Hem Global hem Local olarak kodlanan çalışmalar her iki etkin sayımda da yer alabilir. Bu nedenle bu iki sayım doğrudan toplanarak 298 elde edilmesi beklenmemelidir. Ayrı olarak gösterilen 15 sayısı, Excel özetinde “Both Global & Local” olarak raporlanan değerdir.

## 6. Arama kayıtları ve veri erişilebilirliği

Sistematik incelemede Scopus, Web of Science, IEEE Xplore ve ACM Digital Library gibi bibliyografik veri tabanlarından yararlanılmıştır. Bu depodaki Excel dosyası, inceleme sonunda ana analiz havuzuna alınan çalışmaların kodlanmış kayıtlarını ve bunlara ilişkin betimsel özetleri sunmaktadır.

Bununla birlikte, **orijinal veri tabanı dışa aktarma dosyaları ve tüm arama geçmişini içeren eksiksiz, makine tarafından okunabilir bir kayıt şu anda bu sürümde bulunmamaktadır.**

Bu nedenle:

- Excel dosyası, ana inceleme havuzunu ve kodlama özetlerini incelemek için kullanılabilir.
- Excel dosyası, ham veri tabanı dışa aktarımları olarak tanımlanmamalıdır.
- Mevcut dosyalar, her veri tabanındaki arama sorgusunu, dışa aktarma tarihini, tüm yinelenen kayıtları ve her eleme kararını tek başına yeniden oluşturmayı sağlamaz.
- Ham dışa aktarma dosyaları veya ayrıntılı eleme kayıtları ileride temin edilip depoya eklenirse her dosya; veri tabanı adı, dışa aktarma tarihi, dosya biçimi ve kullanım amacı belirtilerek ayrı şekilde belgelenmelidir.

Bu açıklama, düzenlenmiş analiz veri tabanı ile orijinal arama kayıtları arasındaki farkı açıkça belirtmek ve veri erişilebilirliği konusunda yanlış bir izlenim oluşmasını önlemek amacıyla eklenmiştir.

## 7. Atıf ve kullanım

Bu veri tabanını kullanırken ilgili sistematik literatür incelemesi makalesine atıf verilmesi önerilir. Veri seti için henüz kalıcı bir arşiv kaydı veya DOI oluşturulmadıysa makaleye ve bu GitHub deposuna birlikte atıf yapılabilir; erişim tarihi de belirtilebilir.

- **Sürüm:** 1.0
- **Ana analiz havuzu:** 298 çalışma
- **Yayın dönemi:** 2016–2026
- **Dosya biçimi:** Microsoft Excel (`.xlsx`)

## 8. Sürüm yönetimi ve güncelleme ilkeleri

Veri tabanı güncellenirken aşağıdaki adımların izlenmesi önerilir:

1. Önceki sürümün bir kopyasını koruyun.
2. Çalışma kayıtları değiştiğinde özet sayımlarını aynı dâhil etme ölçütlerine göre yeniden hesaplayın.
3. Her yeni sürüm için güncelleme tarihini ve yapılan değişiklikleri kaydedin.
4. README, GitHub deposu ve makaledeki dosya adlarının birbiriyle tutarlı olduğunu kontrol edin.
5. Gerçekte depoda bulunmayan ham dışa aktarma dosyalarını veya eleme kayıtlarını mevcut olarak tanımlamayın.

## 9. İletişim

Kodlama çerçevesi veya düzenlenmiş çalışma veri tabanına ilişkin sorular için ilgili makalenin sorumlu yazarıyla iletişime geçilebilir.
