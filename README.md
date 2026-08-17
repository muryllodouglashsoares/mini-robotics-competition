# Mini Olimpíada de Robótica

Robô seguidor de linha construído com LEGO Spike Prime para a Mini Olimpíada de Robótica do IFPB.

## 📸 Preview

O repositório inclui registros reais do processo em [`images/`](./mini-robotics-competition/images/) (montagem, testes e conclusão da prova) e em [`videos/`](./mini-robotics-competition/videos/) (construção do robô e funcionamento em teste).

## Sobre

Projeto desenvolvido para participação na Mini Olimpíada de Robótica do IFPB, utilizando a plataforma LEGO Spike Prime. O objetivo foi projetar, montar e programar um robô capaz de seguir uma linha de forma autônoma, usando sensor(es) de cor para interpretar o ambiente — aplicando conceitos de programação, lógica e robótica na resolução dos desafios propostos pela competição.

## Funcionalidades

- [x] Robô seguidor de linha com 2 sensores de cor, programado em blocos (arquivo `Robo_Seguidor_Com_2_Sensores.llsp3`)
- [x] Versão alternativa do robô seguidor de linha com 1 sensor de cor, programada em Python (arquivo `Robo_Seguidor_Com_1_Sensor_Versao_Python.llsp3`)
- [x] Documentação da prova/regras da competição (`docs/Regras.pdf`)
- [x] Registro fotográfico e em vídeo de todo o processo: iniciação, testes e conclusão da prova

## Tecnologias

- LEGO Spike Prime (hub, motores, sensor de cor, estruturas Technic)
- Programação em blocos (Spike Prime — arquivo `.llsp3` de 2 sensores)
- Python (variante do robô com 1 sensor — arquivo `.llsp3` correspondente)

## Como funciona

O robô utiliza sensor(es) de cor para detectar a linha guia e ajustar a direção dos motores em tempo real, mantendo-se sobre o percurso de forma autônoma durante a prova. Duas abordagens de programação foram desenvolvidas: uma com dois sensores (programação em blocos) e outra com um único sensor (versão em Python), permitindo comparar as duas estratégias de leitura de linha.

## Estrutura do projeto

```
mini-robotics-competition/
├── src/
│   ├── Robo_Seguidor_Com_2_Sensores.llsp3               # Programa em blocos, 2 sensores
│   └── Robo_Seguidor_Com_1_Sensor_Versao_Python.llsp3    # Programa em Python, 1 sensor
├── images/     # Fotos do processo (iniciação, testes, conclusão da prova)
├── videos/      # Vídeos da construção e do funcionamento do robô
└── docs/
    └── Regras.pdf    # Regras oficiais da competição
```

## Como executar

Os arquivos `.llsp3` são projetos do **LEGO Spike App** (ou LEGO Education SPIKE App) e requerem:

1. Um Hub LEGO Spike Prime montado com motores e sensor(es) de cor.
2. O aplicativo LEGO Spike App instalado (desktop ou tablet).
3. Abrir o arquivo `.llsp3` correspondente (2 sensores/blocos ou 1 sensor/Python) diretamente no app.
4. Conectar o Hub via Bluetooth ou cabo USB e transferir o programa para execução.

## Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos de:

- Programação (em blocos e em Python)
- Lógica computacional
- Robótica educacional
- Montagem mecânica
- Uso de sensores
- Resolução de problemas
- Trabalho em equipe

## Autor

Muryllo Douglas
