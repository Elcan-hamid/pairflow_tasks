# PayFlow — P2P Transfer QA Assignment

## Layihə haqqında

Bu repository PayFlow P2P (Peer-to-Peer) pul köçürmə funksionallığı üzrə hazırlanmış QA praktiki tapşırığını əhatə edir.

İşin əsas məqsədi təqdim olunmuş tələbləri analiz etmək, mümkün riskləri və qeyri-müəyyənlikləri müəyyənləşdirmək, test ssenariləri hazırlamaq və insident zamanı yaranan problemləri araşdırmaqdır.

Tapşırıq 4 əsas hissədən ibarətdir.

## Tapşırıqlar

### Task 1 — Requirements Analysis

Bu hissədə P2P transfer funksionallığının tələbləri analiz edilmişdir.

- Tələblərdəki qeyri-müəyyənliklər və potensial problemlər müəyyənləşdirilmişdir.
- Hər problem üzrə mümkün risklər və fərziyyələr qeyd edilmişdir.
- Problemlər risk səviyyəsinə görə prioritetləşdirilmişdir.

### Task 2 — Test Design

Bu hissədə funksionallığın yoxlanılması üçün test sənədləri hazırlanmışdır.

- 25 test case
- Decision Table
- Positive, Negative və Boundary test ssenariləri
- Non-functional test ssenariləri

Testlər hazırlanarkən maliyyə əməliyyatlarının düzgünlüyünə, limitlərə, komissiya hesablanmasına, OTP və Idempotency-Key mexanizmlərinə xüsusi diqqət ayrılmışdır.

### Task 3 — Incident Analysis

Təqdim olunmuş sistem logları əsasında baş vermiş insident analiz edilmişdir.

- Hadisələrin xronologiyası hazırlanmışdır.
- Mümkün root cause fərziyyələri irəli sürülmüşdür.
- Potensial defektlər müəyyənləşdirilmiş və prioritetləşdirilmişdir.
- Ətraflı bug report hazırlanmışdır.
- Regression test ideyaları təqdim edilmişdir.

### Task 4 — Final Assessment

Son hissədə QA yanaşması ilə bağlı yekun qiymətləndirmə aparılmışdır.

- Vaxt məhdudiyyəti zamanı testlərin prioritetləşdirilməsi
- Manual və Automation Testing seçimi
- Ən böyük risk və onun azaldılması yolları
- Görülmüş işin özünüqiymətləndirilməsi

## Faylların strukturu

Tapşırıqlar **Microsoft Excel (.xlsx)** və **Microsoft Word (.docx)** formatlarında təqdim edilmişdir.

**Excel faylları haqqında qeyd:** Excel sənədlərində tapşırıqların müvafiq bölmələri ayrı-ayrı worksheet-lərdə (tab-larda) yerləşdirilmişdir. Hər tab özünə aid məlumatları ehtiva edir. Bu struktur sənədlərin oxunmasını və bölmələr arasında keçidi asanlaşdırır.

Word sənədlərində isə analizlər, izahlar və yekun nəticələr müvafiq başlıqlar altında təqdim edilmişdir.

## Test yanaşması

Tapşırıq hazırlanarkən aşağıdakı QA yanaşmalarından istifadə edilmişdir:

- **Risk-Based Testing** — yüksək riskli funksionallıqların prioritetləşdirilməsi.
- **Boundary Value Analysis (BVA)** — məbləğ və limitlərin sərhəd dəyərlərinin yoxlanılması.
- **Equivalence Partitioning** — test məlumatlarının uyğun qruplara ayrılması.
- **Decision Table Testing** — müxtəlif şərtlərin və gözlənilən nəticələrin müqayisəsi.
- **Positive & Negative Testing** — həm düzgün, həm də yanlış giriş məlumatlarının yoxlanılması.

## Qeydlər və məhdudiyyətlər

Tapşırıq təqdim olunmuş API tələbləri və insident logları əsasında hazırlanmışdır.

Bəzi biznes qaydaları və texniki davranışlar tələblərdə tam müəyyənləşdirilmədiyindən, müvafiq qeyri-müəyyənliklər ayrıca sənədləşdirilmişdir.

Test case-lər gözlənilən nəticələr əsasında hazırlanmışdır. Real API mühitində icra nəticələri kimi təqdim edilmir.
