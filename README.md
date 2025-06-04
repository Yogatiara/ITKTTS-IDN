# ITKTTS-IDN

### Yoga Tiara Wiguna

ITKTTS-IDN merupakan dataset yang dibuat untuk keperluan penelitian _Text-To-Speech_ dengan fokus pembicara tunggal berbahasa Indonesia. Dataset ini dibuat oleh mahasiswa bernama Yoga Tiara Wiguna program dari program studi Informatika Institut Teknologi Kalimantan (ITK). Transkrip diambil dari dataset publik [TITML-IDN](https://research.nii.ac.jp/src/en/TITML-IDN.html), [ASR-SIndoDuSC](https://magichub.com/datasets/indonesian-scripted-speech-corpus-daily-use-sentence/), [ASR-IndoCSC](https://magichub.com/datasets/indonesian-conversational-speech-corpus/), dan _audio book_ dari buku berjudul "The Art Of War" dengan mengakses video youtube pada channel [bacasuara](https://www.youtube.com/watch?v=XE5aP5JkPbI&t=33s).

Dataset ini dapat diunduh melalui tautan berikut:\
https://drive.google.com/file/d/1j5Cl-rJJ-LnTEcB5pyXnYkc60CKpd9Rw/view?usp=sharing

## Contoh Audio

_"Prinsip-prinsip ini juga sudah diterapkan dalam politik, bisnis, dan interaksi sehari-hari."_\
[ground truth_ts_1.webm](https://github.com/user-attachments/assets/674e8743-368e-412f-89bb-1b328e25e164)

<br><br>

_"Lihat situasi kondisi dulu, contohnya pantai mana aja itu?"_\
[ground truth_ts_2.webm](https://github.com/user-attachments/assets/da2660d1-ca1d-4088-b4ae-5daf3ab17034)


## Contoh transkrip

ITKTTS001-0001.wav|hai selamat pagi apa kabar?\
ITKTTS001-0002.wav|semoga ujiannya berjalan lancar!

## Statistik Dataset

- **Jumlah Dataset :** 1250 sampel
- **Total Durasi Audio :** 02 jam 04 menit
- **Sample Rate :** 22,005 Hz
- **Format Audio :** WAV, mono, 16-bit PCM
- **Bahasa :** Bahasa Indonesia
- **Umur pembicara :** 22 Tahun
- **logat / aksen :** Jawa dan Samarinda
- **Jumlah Pembicara**: 1 pembicara (Yoga Tiara Wiguna)

## Struktur Folder

```
ITKTTS-IDN
│
├── utterance
│   ├── audio 1.wav
│   ├── audio 2.wav
│   └── ...
│
└── Transkrip.txt
```
