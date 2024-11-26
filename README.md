# NAACL2025-Rebuttal

## Rebuttal to Reviewer MPKE

As seen in the Language-wise ChrF++ Scores on IN22-Conv Doc-Level Test set, the RoPE model outperforms ALiBi, which in turn performs better than SINE. This is consistent with the overall trends reported in the manuscript. 

| Pair                  | FT (SINE; ALiBi; RoPE) | LoRA (SINE; ALiBi; RoPE) | MinLoRA (SINE; ALiBi; RoPE) |
|-----------------------|------------------------------------------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| eng_Latn-asm_Beng     | 40.4; 45.4; 48.9                                           | 29.6; 32.5; 43.5                                                           | 33.9; 36.6; 45.0                                                                          |
| eng_Latn-ben_Beng     | 40.8; 48.3; 51.6                                           | 34.4; 42.7; 43.5                                                           | 34.8; 45.1; 49.8                                                                          |
| eng_Latn-brx_Deva     | 23.1; 25.3; 27.6                                           | 19.1; 15.2; 18.2                                                           | 16.2; 18.7; 14.5                                                                          |
| eng_Latn-doi_Deva     | 42.9; 45.5; 54.9                                           | 29.2; 27.8; 33.1                                                           | 24.7; 29.2; 33.8                                                                          |
| eng_Latn-gom_Deva     | 21.8; 25.6; 25.9                                           | 18.8; 23.2; 26.8                                                           | 19.7; 25.2; 26.9                                                                          |
| eng_Latn-guj_Gujr     | 43.7; 52.2; 55.7                                           | 36.5; 48.0; 54.0                                                           | 36.6; 47.9; 53.4                                                                          |
| eng_Latn-hin_Deva     | 41.6; 49.4; 52.5                                           | 36.7; 45.4; 51.6                                                           | 36.8; 45.9; 52.0                                                                          |
| eng_Latn-kan_Knda     | 33.0; 38.7; 39.7                                           | 28.3; 36.4; 38.7                                                           | 28.5; 35.7; 39.1                                                                          |
| eng_Latn-kas_Arab     | 31.0; 30.7; 36.4                                           | 20.5; 19.1; 23.5                                                           | 23.6; 21.3; 26.7                                                                          |
| eng_Latn-mai_Deva     | 34.8; 44.2; 47.1                                           | 30.5; 33.9; 36.4                                                           | 24.8; 31.0; 34.7                                                                          |
| eng_Latn-mal_Mlym     | 39.7; 48.6; 50.5                                           | 36.3; 43.3; 46.7                                                           | 36.7; 43.6; 48.5                                                                          |
| eng_Latn-mar_Deva     | 38.9; 49.4; 50.3                                           | 33.4; 44.0; 48.8                                                           | 33.1; 43.8; 49.2                                                                          |
| eng_Latn-mni_Mtei     | 32.8; 33.8; 40.9                                           | 23.5; 21.1; 26.1                                                           | 28.2; 19.6; 29.9                                                                          |
| eng_Latn-npi_Deva     | 37.2; 49.2; 51.1                                           | 34.6; 40.0; 48.3                                                           | 32.4; 42.2; 48.5                                                                          |
| eng_Latn-ory_Orya     | 34.7; 42.1; 43.1                                           | 28.8; 36.3; 41.2                                                           | 30.0; 37.2; 41.4                                                                          |
| eng_Latn-pan_Guru     | 44.5; 52.8; 55.4                                           | 36.1; 41.7; 52.9                                                           | 39.4; 45.3; 54.3                                                                          |
| eng_Latn-san_Deva     | 29.9; 31.2; 35.8                                           | 21.6; 16.9; 21.3                                                           | 21.1; 17.0; 27.4                                                                          |
| eng_Latn-sat_Olck     | 33.0; 33.0; 34.1                                           | 21.2; 12.9; 16.0                                                           | 11.7; 5.8; 8.8                                                                            |
| eng_Latn-snd_Deva     | 27.4; 33.6; 33.6                                           | 21.6; 17.9; 24.2                                                           | 20.2; 19.2; 27.8                                                                          |
| eng_Latn-tam_Taml     | 41.5; 47.1; 48.1                                           | 35.0; 42.9; 46.5                                                           | 36.2; 44.0; 46.2                                                                          |
| eng_Latn-tel_Telu     | 38.3; 48.1; 49.9                                           | 33.2; 44.5; 48.2                                                           | 32.7; 42.6; 48.2                                                                          |
| eng_Latn-urd_Arab     | 46.2; 57.6; 60.1                                           | 41.3; 51.3; 60.1                                                           | 42.5; 52.4; 60.5                                                                          |
 
 
| Pair                  | FT (SINE; ALiBi; RoPE) | LoRA (SINE; ALiBi; RoPE) | MinLoRA (SINE; ALiBi; RoPE) |
|-----------------------|------------------------------------------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| asm_Beng-eng_Latn     | 38.4; 54.7; 59.2                                           | 35.5; 47.5; 59.2                                                           | 33.1; 42.2; 57.9                                                                          |
| ben_Beng-eng_Latn     | 45.9; 55.8; 59.7                                           | 45.8; 52.6; 58.3                                                           | 41.5; 48.8; 57.3                                                                          |
| brx_Deva-eng_Latn     | 41.8; 51.0; 56.2                                           | 39.4; 45.8; 54.2                                                           | 37.2; 42.5; 54.7                                                                          |
| doi_Deva-eng_Latn     | 42.2; 55.0; 61.6                                           | 39.3; 46.2; 58.8                                                           | 36.7; 44.9; 57.9                                                                          |
| gom_Deva-eng_Latn     | 38.8; 48.6; 53.8                                           | 38.5; 41.0; 52.2                                                           | 33.9; 37.3; 50.3                                                                          |
| guj_Gujr-eng_Latn     | 46.2; 57.7; 63.1                                           | 42.7; 55.0; 61.8                                                           | 39.5; 52.4; 61.2                                                                          |
| hin_Deva-eng_Latn     | 44.7; 57.1; 60.4                                           | 43.9; 53.9; 59.7                                                           | 39.6; 53.0; 59.2                                                                          |
| kan_Knda-eng_Latn     | 37.1; 44.6; 51.5                                           | 34.8; 43.8; 49.3                                                           | 30.3; 41.5; 48.3                                                                          |
| kas_Arab-eng_Latn     | 34.4; 46.7; 49.2                                           | 33.3; 39.3; 47.3                                                           | 31.4; 33.3; 42.7                                                                          |
| mai_Deva-eng_Latn     | 42.7; 54.0; 58.2                                           | 42.5; 49.1; 56.2                                                           | 38.1; 46.0; 54.7                                                                          |
| mal_Mlym-eng_Latn     | 38.5; 51.8; 57.1                                           | 38.3; 48.2; 55.6                                                           | 33.7; 44.5; 54.4                                                                          |
| mar_Deva-eng_Latn     | 45.9; 55.7; 61.2                                           | 44.5; 53.4; 59.0                                                           | 38.8; 47.6; 57.5                                                                          |
| mni_Mtei-eng_Latn     | 32.3; 45.9; 51.2                                           | 31.0; 37.6; 50.2                                                           | 26.9; 35.2; 48.8                                                                          |
| npi_Deva-eng_Latn     | 47.5; 58.5; 62.5                                           | 44.3; 55.2; 61.0                                                           | 41.1; 52.7; 60.7                                                                          |
| ory_Orya-eng_Latn     | 42.9; 54.8; 59.4                                           | 41.7; 49.3; 58.7                                                           | 38.8; 49.0; 58.6                                                                          |
| pan_Guru-eng_Latn     | 37.4; 53.5; 58.3                                           | 37.5; 50.6; 59.2                                                           | 33.6; 44.9; 57.3                                                                          |
| san_Deva-eng_Latn     | 37.9; 47.2; 50.5                                           | 35.5; 42.2; 48.9                                                           | 32.8; 38.4; 48.3                                                                          |
| sat_Olck-eng_Latn     | 33.4; 43.1; 48.5                                           | 30.2; 39.1; 44.1                                                           | 29.7; 32.4; 41.2                                                                          |
| snd_Deva-eng_Latn     | 36.9; 45.4; 50.9                                           | 32.6; 36.9; 49.8                                                           | 30.9; 35.2; 43.8                                                                          |
| tam_Taml-eng_Latn     | 38.1; 47.9; 52.2                                           | 36.8; 46.7; 51.0                                                           | 33.4; 43.7; 50.2                                                                          |
| tel_Telu-eng_Latn     | 41.8; 52.2; 57.1                                           | 40.8; 48.0; 55.2                                                           | 37.7; 46.4; 54.3                                                                          |
| urd_Arab-eng_Latn     | 42.2; 58.8; 63.8                                           | 44.0; 54.2; 61.9                                                           | 38.5; 51.1; 61.1                                                                          |



## Rebuttal to Reviewer DeLa

The table below describes the performance (in terms of the ChrF++ score), immediately after swapping the Positional Embeddings. The legend for the table is as follows:
- N* : Removal of Sinusoidal PE from the base model
- R* : Direct Substitution of Sinusoidal PE with RoPE
- A* : Direct Substitution of Sinusoidal PE with ALiBi

These results can be compared with Table-5 and Table-6 to observe the gains after fine-tuning and re-alignment. 

| Direction   | Benchmark           | N*   | R*   | A*   |
|-------------|----------------------|-------|-------|-------|
|**Indic-En** | IN22-Gen             | 34.1  | 28.0  | 19.5  |
|             | IN22-Conv            | 38.6  | 38.0  | 35.0  |
|             | Flores               | 34.9  | 31.5  | 23.3  |
|**En-Indic** | IN22-Gen             | 30.1  | 24.9  | 13.4  |
|             | IN22-Conv            | 35.2  | 31.3  | 26.1  |
|             | Flores               | 31.5  | 27.0  | 15.9  |  
 
| Direction   | Benchmark           | N*   | R*   | A*   |
|-------------|----------------------|-------|-------|-------|
|**Indic-En** | ALT                  | 39.5  | 35.4  | 26.8  |
|             | IN22-Conv            | 10.2  | 2.3   | 1.1   |
|             | Flores               | 28.6  | 12.4  | 5.6   |
|**En-Indic** | ALT                  | 36.7  | 31.9  | 19.4  |
|             | IN22-Conv            | 7.7   | 2.7   | 1.3   |
|             | Flores               | 23.8  | 14.8  | 4.8   |

