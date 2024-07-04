# Codes_from_MAC0417
Several programming exercises (EPs) developed for a College class (MAC 0417 - Image Processing and Visualization)

# Links Úteis:
- Notebook (Google Colab) do EP01: https://colab.research.google.com/drive/1VfJfxVY7hDao9u2Vvc8k26umqTzVSfG_?authuser=1#scrollTo=ZCXVbx4dNVF4
  
- 1º Notebook (Google Colab) do EP02: https://colab.research.google.com/drive/1Nw1ZBk85BCnBKDn7audb7VXTjCoZyy52?usp=sharing

- 2º Notebook (Google Colab) do EP02: https://colab.research.google.com/drive/12bovrcDCfp-pFnGsp85xXA6W0Va5m28-?usp=sharing

- Pasta (Google Drive) dos EPs: https://drive.google.com/drive/folders/1ubIiGba3zHnV96B1JR5jz7j8Usq4PoZH?usp=drive_link

# EP01:
- Criação de uma base de imagens;
- Elaboração de um notebook em python (.ipynb) contendo os metadados das imagens, tabela sumária, tabela detalhada por classe e uma apresentação das imagens obtidas.

# EP02:

## EP02-1: Data augmentation
- Elaboração de um notebook em python (.ipynb) contendo funções para fazer data augmentation do dataset do EP01;
- Criar 6 funções de data augmentation. Cada função será aplicada a cada imagem do dataset do EP01, sendo estas funções:
    - RGB2gray (converter as imagens RGB originais em níveis de cinza);
    - Contrast Stretching;
    - Logaritmo da imagem;
    - Exponencial da imagem;
    - Laplaciano da imagem;
    - Filtro da média implementado usando convolução;
- Salvar essas alterações em pastas no drive.

## EP02-2: Normalização e análise da variação das classes
- Elaboração de um notebook em python (.ipynb) que realize a normalização das imagens de cada classe do dataset de augmentation;
- Usar a equalização de histogramas como função inicial de normalização, gerando um normalizedDataset;
- Aplicar as seguintes funções de análise à cada classe presente nos datasets originalGrayDataset, augmentedDataset e normalizedDataset:
    - Protótipo médio de cada classe;
    - Histograma médio de cada classe;
    - Variância do histograma de cada classe.
