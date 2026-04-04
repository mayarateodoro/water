# Mapeamento de Água com Séries Temporais Sentinel-2

## Descrição do Projeto

Este repositório contém um pipeline automatizado em **R** para mapeamento de recursos hídricos (água) na ecorregião do **Planalto Central**, usando imagens **Sentinel-2** e o pacote **SITS** (Satellite Image Time Series). 
O fluxo integra:

- Pré-processamento e cálculo de índices espectrais (MNDWI, SAVI, NDWI)
- Modelo Linear de Mistura Espectral (MLME) para frações de solo, vegetação e água
- Redução de desbalanceamento de amostras
- Treinamento de **Random Forest** com validação via mapas auto-organizáveis (SOM)
- Classificação temporal (2022 e 2024)
- Pós-processamento com suavização espacial e mosaico
- Geração de mapa de confiança e estatísticas de acurácia

---

## Área de Estudo

- **Ecorregião:** Planalto Central (Cerrado brasileiro)
- **Período de análise:** Maio a Agosto (seco)
- **Anos:** 2022 e 2024
- **Satélite:** Sentinel-2 (16 dias de composição)

---


