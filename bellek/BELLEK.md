# AI Model Radar Bellek Dosyasi
Son guncelleme: 2026-06-14

## Tahmin Dogruluk Takibi

| Tarih | Tahmin | Gerceklesti mi |
|---|---|---|
| 2026-05-25 | Ilk rapor — tahmin baslangici | — |
| 2026-05-25 | Gemini 3.5 Pro Haziran basi GA | KISMI — hala onizleme, GA Haziran sonuna (23/30) kaydi |
| 2026-05-25 | Llama 4 Behemoth | HAYIR — hala ortada yok |
| 2026-05-25 | Muse Spark detaylari | HAYIR — yeni detay gelmedi |
| 2026-05-25 | Unity AI genislemesi | KISMI — Muse devam, spesifik duyuru yok |
| 2026-05-25 | Anthropic Stainless entegrasyonu | HAYIR — haber yok |

## En Hizli Haber Kaynaklari

| Kaynak | Guc | Not |
|---|---|---|
| anthropic.com/news | Anthropic icin birincil | WebFetch calisiyor, tarihli liste veriyor |
| llm-stats.com/llm-updates | TUM model surumleri gunluk hub | EN VERIMLI tek kaynak — tarihli, lisans bilgili |
| llm-stats.com/benchmarks/swe-bench-verified | SWE-Bench Verified guncel skorlar | Kodlama icin birincil benchmark |
| openai.com/news | HTTP 403 | WebSearch ile gecil |
| techtimes/codersera/wavespeed | Gemini sizinti/tahmin | Release penceresi tahminleri icin |
| HuggingFace trending (presenc.ai aynasi) | OSS model trendleri | Cin modelleri agirlikli |

## Benchmark Tarihi

| Tarih | Olay |
|---|---|
| 2026-05-25 | MMLU/HumanEval satured. Oncelikli: GPQA Diamond, SWE-Bench Verified, Terminal-Bench 2.0 |
| 2026-06-14 | SWE-Bench Verified: Mythos 5 %95.5*, Fable 5 %95*, Opus 4.8 %88.6, GPT-5.5 %82.6, Gemini 3.5 Flash %78.8 (*kapatildi) |
| 2026-06-14 | Arena Text Elo: Grok-4.1 Thinking 1483. Arena Hard: GPT-5.6 Pro ~1465, Mythos 5 ~1458. Top 8 ~55 Elo icinde (rekor sıkilik) |
| 2026-06-14 | Indie icin fiili kodlama lideri: Claude Opus 4.8 (%88.6) — Mythos/Fable erisilemez |

## One Cikan Trendler

1. **Devlet mudahalesi yeni risk:** ABD ihracat kontrolu Fable 5/Mythos 5'i 72 saatte kapatti (9 Haz cikti, 12 Haz kapandi). Frontier modeller jeopolitik riske acik.
2. **YABANCI UYRUKLU ERISIM ENGELI:** Direktif ABD disi + yabanci uyruklulari kapsiyor. Mehmet (Turk) icin Fable 5/Mythos 5 erisilemez — bu modelleri onerme.
3. Fiyat dususu suruyor: DeepSeek V4 Flash $0.14/$0.28; cache'de ~%90 indirim standart.
4. Cin OSS konverjansi: 2 haftada 6 surum (Qwen 3.7, DeepSeek V4.1, Hunyuan Large 3, ERNIE 5.1, Doubao Pro, GLM-6). HF Top 10'un 5'i Cin.
5. Motor-gomulu AI: Unity Muse + Unreal AI assistant cekirdek strateji. AAA stüdyolarin %78'i AI kullaniyor (GDC).
6. Benchmark satured devam: pratikte SWE-Bench Verified + Arena Elo ayristirici.

## Indie Dev icin Kanitlanmis Kullanimlar

| Kullanim | Onerilen Model | Not |
|---|---|---|
| Buyuk oyun script / ajan | Claude Opus 4.8 | Erisilebilir frontier lider, $5/$25 |
| NPC diyalogu / hikaye | Claude Haiku 4.5 | Hizli + ucuz |
| Ucretsiz prototip | Gemini 3.5 Flash | Ucretsiz tier + hiz |
| Budget API | DeepSeek V4 Flash ($0.14) | MIT lisans, yuksek hacim |
| Lokal | Qwen 3.7 / Kimi K2.7 | Guclu GPU varsa sifir maliyet |
| 3D asset | Meshy / Tripo | 30-60s, metin->oynanabilir |
| 2D asset | Scenario / Layer | Stil tutarliligi |
| Ses/muzik | ElevenLabs + Suno | SFX + muzik |
| Editor ici | Unity Muse / Unreal AI | Motor-gomulu |

## Yaklasan Buyuk Cikislar (Bilinen)

| Model | Sirket | Beklenen | Durum |
|---|---|---|---|
| Gemini 3.5 Pro GA | Google | Haziran sonu (23/30) | Vertex onizlemede, 2M baglam + Deep Think |
| Fable 5 / Mythos 5 geri donus | Anthropic | Belirsiz | Anthropic direktife itiraz ediyor; yabanci erisim suplu |
| Grok 5 | xAI | Gecikmis | Haziran dalgasinda soylenti |
| Claude Sonnet 4.8 | Anthropic | Soylenti | Dogrulanmadi |
