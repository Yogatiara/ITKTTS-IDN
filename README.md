# ITKTTS-IDN

### Yoga Tiara Wiguna

ITKTTS-IDN merupakan dataset yang dibuat untuk keperluan penelitian _Text-To-Speech_ dengan fokus pembicara tunggal berbahasa Indonesia. Dataset ini dibuat oleh mahasiswa bernama Yoga Tiara Wiguna program dari program studi Informatika Institut Teknologi Kalimantan (ITK). Transkrip diambil dari dataset publik [TITML-IDN](https://research.nii.ac.jp/src/en/TITML-IDN.html), [ASR-SIndoDuSC](https://magichub.com/datasets/indonesian-scripted-speech-corpus-daily-use-sentence/), [ASR-IndoCSC](https://magichub.com/datasets/indonesian-conversational-speech-corpus/), dan _audio book_ dari buku berjudul "The Art Of War" dengan mengakses video youtube pada channel [bacasuara](https://www.youtube.com/watch?v=XE5aP5JkPbI&t=33s).

Dataset ini dapat diunduh melalui tautan berikut:\
https://drive.google.com/file/d/1j5Cl-rJJ-LnTEcB5pyXnYkc60CKpd9Rw/view?usp=sharing

## Contoh Audio

<div style="text-align: center">
  <p>
    <i>
        "Prinsip-prinsip ini juga sudah diterapkan dalam politik, bisnis, dan interaksi sehari-hari."
    </i>
  </p>
  <audio controls="1" controlslist="nodownload nofullscreen noremoteplayback">{ip}{form_title}{ip}

   <source src="https://www.dropbox.com/scl/fi/325qimcclvl1c24l48zpl/ground-truth_ts_1.wav?rlkey=zyjcg9njd3dvc45ie7nhssa1q&st=krj00nne&raw=1" type="audio/wav" />
 </audio>

<br><br>

  <p>
    <i>
        "Lihat situasi kondisi dulu, contohnya pantai mana aja itu?"
    </i>
  </p>
  <audio controls="1" controlslist="nodownload nofullscreen noremoteplayback">{ip}{form_title}{ip}

   <source   src="https://www.dropbox.com/scl/fi/olsqedkjdey1zpr3z0sod/ground-truth_ts_2.wav?rlkey=s69481z689hrdtqhrsal2e1e2&st=eh2tjgs7&raw=1" type="audio/wav" />
 </audio>
</div>

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
