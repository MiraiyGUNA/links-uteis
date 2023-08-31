## FFMPEG

### Código Base

`ffmpeg -i [nome do input].[extensão do ficheiro] [nome que queres de output].[extensão nova]`

### Transformar Frames em um Vídeo

```
ffmpeg -framerate 60 -i img%04d.png output.mp4
```

-framerate [número de fps]

[nomedoficheiro]%04d(número de números, que os frames tem // o "4" é porque existem quatro números, no total, no nome do ficheiro. Ou seja, entra o "0001" e também o "9999" // é obrigatório ter o "%" e o "d" porque, se não, o programa vai procurar um arquivo chamado "04d").[extensão dos arquivos]