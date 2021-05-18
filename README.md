# Primeiro projeto da disciplina CC53B-Organização de Computadores-2019-1    
Desenvolver uma solução em assembly (MIPS 32) que, dada uma sequencia de imagens finita (câmera fixa), calcule o modelo de fundo.    
Utilizamos o simulador MARS (MIPS Assembler and Runtime Simulator).    
A imagens de input e output precisam estar no formato PGM (portable graymap format) ou PPM (portable pixmap format).

## Exemplo 1 (escala de cinza)

Input
<p align="center">
  <img src="https://i.imgur.com/CLigl1n.png" width="160">
  <img src="https://i.imgur.com/H23RQRR.png" width="160">
  <img src="https://i.imgur.com/A9WppaA.png" width="160">
  <img src="https://i.imgur.com/bDKOycj.png" width="160">
  <img src="https://i.imgur.com/ti2eToU.png" width="160">
  <img src="https://i.imgur.com/t0szv7i.png" width="160">
  <img src="https://i.imgur.com/F7DxMDq.png" width="160">
  <img src="https://i.imgur.com/RWz3f0M.png" width="160">
  <img src="https://i.imgur.com/Bdms4cI.png" width="160">
  <img src="https://i.imgur.com/1Nikp0m.png" width="160">
</p>
Output
<p align="center">
  <img src="https://i.imgur.com/3ckmRQN.png" width="700">
</p>

## Exemplo 1 (colorido)
Input
<p align="center">
  <img src="https://i.imgur.com/6CUmXtN.png" width="160">
  <img src="https://i.imgur.com/TYLGRYA.png" width="160">
  <img src="https://i.imgur.com/MirZmPI.png" width="160">
  <img src="https://i.imgur.com/VqX9sS1.png" width="160">
  <img src="https://i.imgur.com/PvyuiV0.png" width="160">
  <img src="https://i.imgur.com/kGhsEFH.png" width="160">
  <img src="https://i.imgur.com/8CH58vF.png" width="160">
  <img src="https://i.imgur.com/I5oa2os.png" width="160">
  <img src="https://i.imgur.com/3SQNDIs.png" width="160">
  <img src="https://i.imgur.com/JVntmbb.png" width="160">
</p>
Output
<p align="center">
  <img src="https://i.imgur.com/tbXU3kB.png" width="700">
</p>

## Exemplo 2 (escala de cinza)

Input
<p align="center">
  <img src="https://i.imgur.com/cGy1fY6.png" width="160">
  <img src="https://i.imgur.com/j60kTgN.png" width="160">
  <img src="https://i.imgur.com/UqiKysD.png" width="160">
  <img src="https://i.imgur.com/HMd4Dsu.png" width="160">
  <img src="https://i.imgur.com/zPokZVb.png" width="160">
  <img src="https://i.imgur.com/AmuOKve.png" width="160">
  <img src="https://i.imgur.com/K333N5r.png" width="160">
  <img src="https://i.imgur.com/p0T6f3B.png" width="160">
  <img src="https://i.imgur.com/Z4kbD5I.png" width="160">
  <img src="https://i.imgur.com/s9aaNNV.png" width="160">
</p>
Output
<p align="center">
  <img src="https://i.imgur.com/MQF3Wj6.png" width="700">
</p>

## Exemplo 2 (colorido)

Input
<p align="center">
  <img src="https://i.imgur.com/0RQB2V7.png" width="160">
  <img src="https://i.imgur.com/Upvm12j.png" width="160">
  <img src="https://i.imgur.com/e5mCdUD.png" width="160">
  <img src="https://i.imgur.com/I3nN6cI.png" width="160">
  <img src="https://i.imgur.com/VGIacRD.png" width="160">
  <img src="https://i.imgur.com/NMSCgCs.png" width="160">
  <img src="https://i.imgur.com/cB5cAof.png" width="160">
  <img src="https://i.imgur.com/5XqFzxy.png" width="160">
  <img src="https://i.imgur.com/IY2bywA.png" width="160">
  <img src="https://i.imgur.com/u3oHmfc.png" width="160">
</p>
Output
<p align="center">
  <img src="https://i.imgur.com/W4Hwp5k.png" width="700">
</p>

## Como usar
- Execute o programa
- Insira o nome/caminho com extensão e % (foto%.ppm)
- Insira a quantidade de arquivos (Max 10)
- Se tudo ocorreu bem: resultado.pgm (.ppm)

_________________________________________________
*All copyrighted content (images, codes, etc.) belong to their respective owners and are not included under the license of this repositorie.*
