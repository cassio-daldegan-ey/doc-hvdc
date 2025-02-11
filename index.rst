.. doc-hvdc documentation master file, created by
   sphinx-quickstart on Fri Feb  7 13:35:16 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Documentação EV 41 - HVDC Termografia
=====================================

Essa documentação está separada em cinco categorias:

* **Introdução**: Visão geral sobre o projeto, compreendendo seus princiapis objetivos.

* **Pré-processamento**: Extração dos dados utilizados no modelo (dados de câmeras termográficas e dados do SAGE) e tratamento dos dados para servirem de insumo dos modelos de previsao e para gerar as estatísticas descritivas utilizadas no dashboard.

* **Modelos preditivos**: Rotina de treinamento e previsão dos modelos de série temporal.

* **Pós-processamento**: Tratamento das bases de dados para serem utilizadas no dashboard.

* **Dashboard**: Explicacão sobre os visuais do dashboard.

.. toctree::
   :maxdepth: 2
   :caption: Conteúdo:
   
   introducao
   data_processing
   model
   post_processing
   dash