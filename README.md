# CC7711 - Inteligência Artificial e Robótica

## Laboratório 7 - Visão Computacional

Alunos:
- Fabio Augusto Schiavi Morpanini | RA: 22.121.094-1
- Felipe de Campos Oka            | RA: 22.121.001-6

### Relatório

Para realizar a atividade proposta em sala de aula, foi utilizado dos arquivos disponibilizados no Github do professor Ricardo Destro. Para realizar a captação dos contornos, foram utilizadas as imagens: <br>
- Girafa.jpeg
- Aviao.jpeg
- Satelite.jpeg

Em todos os casos, buscamos obter o melhor resultado de contornos da imagem captado durante o estudo, contudo, devido aos resultados dos extremos das variações dos dados, não foi possível captar o contorno perfeito de cada imagem.
No estudo da última imagem (Satelite.jpeg) foi realizado dois estudos:

1. thresh: para este caso, foi utilizado como base a imagem gerada pela conversão do RGB para preto e branco
<div align="center">
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/edf9cb20-7b3b-4346-b532-08b70ca37bfa" width="600px" />
</div>

2. edges_gray: para este, foi utilizada a imagem com detecção de bordas da imagem gerada pelo “thresh” com detecção de bordas de Canny, com e sem blurry
<div align="center">
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/8245cd99-325d-4109-be84-217c5899e62e" width="600px" />
</div>

## Girafa.jpeg
<div align="center">
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/24bcf77a-3996-4fd3-a776-a93f887c3e21" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/2eadadac-38e5-43fd-9aea-5400cf4280c9" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/cb9be865-5e49-41db-9d14-7249804dee71" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/a88ff056-18db-4bcc-aa79-452cb96eca69" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/98d97357-cbcf-421d-baa1-0a959e0b38e1" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/f3ea3d9c-65f2-49d5-a9c0-248f56792971" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/9624ef25-2403-4b40-9683-0947d2ae2933" width="200px" />

<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/9ba493ec-2279-4fa3-a865-6397616fbb2d" width="500px" />
</div>

## Aviao.jpeg
<div align="center">
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/7d861006-fb59-46d6-9a12-c10f3b6b0128" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/ae520daf-7990-466c-80ad-673b873dd9cd" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/d00ccd49-9380-470f-9a4f-8befae3b1f35" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/b4766dee-af87-4d47-82e5-ce4112f84f36" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/13cc5664-ca25-45df-ac87-f4e2b56b0b36" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/2eb7c29b-cf2d-47b7-9338-c49538f6a1ed" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/40a69a87-0241-41ad-ac08-2fafe257b24c" width="200px" />
  
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/92b057df-5280-47ed-bfcc-421195614c8b" width="500px" />
</div>

## Satelite.jpeg - Estudo com Thresh
<div align="center">
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/f6ad0dbb-fdd6-4d4e-a98d-3ec93d6550a6" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/a6e6d42e-0b89-4981-a741-de037548b4b0" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/6eb55ca6-eed4-41e1-99f5-f997e0f49da9" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/6a1221a4-5e99-4de0-a7c4-7741cf32ef4b" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/1d462481-c583-460b-961c-cb20b7fc7f98" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/8f946785-6c73-4ab2-9fc8-8d8b745b5f6d" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/79cc0b4b-ac93-4c73-92da-a998cad76715" width="200px" />

<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/9ad0679d-1c6d-4205-9e33-918c7407e8b3" width="500px" />
</div>

## Satelite.jpeg - Estudo com Edges_gray
<div align="center">
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/5913e681-b8e4-476e-a235-83180419b296" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/de569f29-2503-45c2-9b1c-c347a4b638a2" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/f2bce17d-ab98-40fb-a6eb-041c22faf40a" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/f53122f6-71f0-4ac8-a2ab-e34371a08eb7" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/060c0a80-bf9d-46bf-8aae-b39bc7155a00" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/18cea66f-cc86-48ce-81d4-6d286bafadfb" width="200px" />
<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/8102a344-c630-48e1-b557-71a0b7fb56e5" width="200px" />

<img src="https://github.com/KaburauNero/lab07IA/assets/92650933/1e6fdd18-2a48-4f6d-a75c-e379c1bae199" width="500px" />
</div>

### Conclusão 

Durante o estudo, notamos que dependendo dos valores utilizados na conversão de imagem para preto e branco, no tamanho do Kernel e na detecção de bordas com e sem blurry, os contornos das imagens podem ficar muito distorcidos. Para cada imagem, foi necessário realizar vários testes até se adquirir um resultado agradável. 
Notamos também, que não obrigatoriamente, dependendo da imagem de base utilizada no contorno, o mesmo será gerado em torno das áreas mais claras ou mais escuras da imagem, como apresentado no estudo da imagem Satelite.jpeg
