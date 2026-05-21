# Amostragem de Sinais

Projeto de estudo sobre amostragem, subamostragem e filtragem de sinais de audio. O exercicio usa um arquivo `.wav` como entrada, analisa seu espectro de frequencias e gera versoes processadas com e sem filtro passa-baixas.

## Arquivos

- `exercicio_amostragem.ipynb`: notebook principal do exercicio.
- `espectro.py`: funcao auxiliar para plotar o espectro de magnitude de um sinal usando FFT.
- `filtro.py`: funcao auxiliar para criar um filtro FIR passa-baixas com janela de Hamming.
- `creed_overcome.wav`: audio original usado no experimento.
- `saida_original_mono.wav`: audio original convertido para mono.
- `saida_filtrado.wav`: audio apos filtragem.
- `saida_subamostrado_sem_filtro.wav`: audio subamostrado sem filtragem previa.
- `saida_subamostrado_com_filtro.wav`: audio subamostrado apos filtragem.
- `Amostragem.pdf`: material de apoio do exercicio.

## Dependencias

Para executar o notebook, instale:

```bash
pip install numpy scipy matplotlib ipython jupyter
```

## Como executar

1. Clone o repositorio:

```bash
git clone https://github.com/alvaroalmeida22/amostragem-de-sinais.git
cd amostragem-de-sinais
```

2. Abra o notebook:

```bash
jupyter notebook exercicio_amostragem.ipynb
```

3. Execute as celulas em ordem para gerar os graficos e arquivos de audio processados.

## Tema do experimento

O notebook explora conceitos de processamento digital de sinais, incluindo:

- leitura e manipulacao de arquivos de audio;
- conversao para sinal mono;
- visualizacao do espectro de frequencias;
- projeto de filtro FIR passa-baixas;
- comparacao entre subamostragem com e sem filtro anti-aliasing.
