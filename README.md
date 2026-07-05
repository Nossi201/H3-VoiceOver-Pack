# H3-VoiceOver-Pack

Wygenerowane audio i wyekstrahowane teksty kampanii **Heroes Chronicles** (Heroes of Might and Magic III), używane
przez [H3AudioNarrator](https://github.com/Nossi201/H3AudioNarrator) do automatycznego odtwarzania narracji
podczas okien dialogowych kampanii.

Podłączane do `H3AudioNarrator` jako git submoduł (`tools/chronicles_voiceover`).

## Zawartość

- `campaign_extracted/` — wyekstrahowane teksty dialogowe z plików `.lod` wszystkich rozdziałów Chronicles
- `campaign_final/` — wersje robocze/finalne tekstów po ręcznej redakcji
- `audio_prepared/` — teksty przygotowane pod generację (podział na segmenty/głosy)
- `audio_woj_campaign/` — gotowe, wygenerowane audio (ElevenLabs) dla kampanii "Wojownicy Pustkowi" + `text_map*.txt`
- `audio_final/` — przykładowe/testowe wygenerowane dialogi wieloosobowe

Kolejne rozdziały Chronicles (Bun, Drz, H3ab, Mie, Ogn, Pod, Sza, Wla...) mają na razie tylko wyekstrahowane
teksty w `campaign_extracted/` — audio jeszcze nie wygenerowane.

Prawa do oryginalnych tekstów i fabuły należą do twórców Heroes of Might and Magic III / Heroes Chronicles.
Ta zawartość to fanowski dodatek audio (narracja generowana przez AI), nie oficjalny materiał.
