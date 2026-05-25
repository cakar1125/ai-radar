# AI Model Radar
# GRUP A — Pazartesi, Çarşamba, Cuma, Pazar | 10:00 UTC (13:00 İstanbul)

Bugünün tarihini belirle (YYYY-MM-DD). Yapay zeka model piyasasındaki son gelişmeleri araştır ve raporla.

NOT: Repo zaten mevcut dizinde. git komutu KULLANMA. Dosyaları write_file aracıyla yaz.

## ADIM 1 — Önceki raporları oku

list_files ile raporlar/ klasörünü kontrol et. Son 2 raporu read_file ile oku. Önceki haberleri tekrarlama.

## ADIM 2 — Web araması

web_search ile şunları ara:
- "new AI model released today"
- "AI model benchmark [mevcut ay]"
- "OpenAI Anthropic Google DeepMind news today"
- "open source LLM release this week"

Ayrıca fetch_url ile `https://r.jina.ai/https://huggingface.co/models?sort=modified` al.

## ADIM 3 — Raporla

write_file ile `raporlar/YYYY-MM-DD_ai-radar.md` oluştur:

```
# [YYYY-MM-DD] AI Model Radar

## Bugünün Öne Çıkanı
[En önemli gelişme - 2-3 cümle]

## Yeni Modeller / Güncellemeler
| Model | Şirket | Ne Değişti | Önem |
|---|---|---|---|
...

## Benchmark Liderleri (Güncel)
| Görev | Lider Model | Skor |
|---|---|---|
...

## Indie Oyun Dev İçin Önemi
[Bu hafta çıkan modellerin oyun geliştirme araçlarına etkisi - 2-3 cümle]

## Gelecek Hafta Beklenenler
[Açıklanan ama henüz çıkmayan modeller]
```
