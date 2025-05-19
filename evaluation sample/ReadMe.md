In this folder, we place some test data generation samples. It includes five-character poetry, seven-character poetry, Song iambics, and Shijing poetry. 

Five-character poetry and seven-character poetry are used in the major experiment compared with other models, while Song iambics and Shijing poetry are used in universality study. Since only five-character poetry and seven-character poetry are in PISSet, there are no groungtruth audio for Song iambics and Shijing poetry.

For each poem, all of its features including Chinese, pronunciation, tone, rhyme and stop token are presented in text.txt, while the pieces of audio named 'FastSpeech2', 'DiffSpeech', 'VITS2', 'Ours' are synthesized by different models and the one named Groundtruth is the original audio in PISSet.

For tones, '平' stands for 'ping (P)', '上' stands for 'shang (S)', '去' stands for 'qu (Q)' and '入' stands for 'ru (R)'.