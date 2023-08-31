### Settings Compressão de Vídeos no Handbrake

Estas são as configurações mais gamers, para comprimir sem perder qualidade

**📷️ vídeo**

- h265 10bits
- slow
- 32cq // 24rf

**🕪 audio**

- opus
- 192 (stereo) // 512 (5.1) // 768 (7.1)

> existem aparelhos antigos que não suportam estas definições, mas quem tem uma dessas, não toca em compressão de ficheiros
> se não são os macacos do áudio, podem reduzir os bitrates
> se não são os macacos do vídeo, podem diminuir mais a qualidade
> se forem zoomers e com attention span de merda, podem usar fast ao invés de slow

_testes que fiz com um vídeo de 957,7 MiB_

```
H265.10bits
85%CPU
50%GPU
5minutos e 40
264,8MiB

H265
85%CPU
50%GPU
5minutos e 22
268,5

H264
80%CPU
55%GPU
5minutos e 22
327,8
```