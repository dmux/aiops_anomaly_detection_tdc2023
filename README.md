# aiops_anomaly_detection_tdc2023

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dmux/aiops_anomaly_detection_tdc2023/main?labpath=outlier.ipynb)

## Overview

Esse repositório contém o código fonte da palestra: AIOPs - Detecção de anomalias com Python e Prometheus,  realizada no Evento TDC 2023 <https://thedevconf.com/tdc/2023/business/trilha-community-lounge-quinta>.

## Requisitos

- Python 3.11.4
- Jupyterlab 4.0.5
- Pandas 2.0.3
- Prophet 1.1.4
- Plotly 5.16.1

## Executando no binder

Para executar o notebook, basta clicar no botão `launch binder` acima.

## Executando localmente

Para executar o notebook localmente, basta executar os seguintes comandos:

```bash
git clone https://github.com/dmux/aiops_anomaly_detection_tdc2023.git
cd aiops_anomaly_detection_tdc2023
poetry shell
poetry install
jupyter lab
```
