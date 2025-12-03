# Sistema Multiagente para Reparto Urbano con Ventanas de Tiempo  
### Trabajo Final – Tópicos en Ciencias de la Computación (CST)

Este proyecto implementa un **Sistema Multiagente (SMA)** para la simulación de un escenario de reparto urbano.  
Cada agente actúa como un repartidor autónomo capaz de:

- Evaluar pedidos considerando distancia, carga y ventanas de tiempo.  
- Comunicarse mediante CFP/PROPOSE/ACCEPT/REJECT.  
- Transferir pedidos (REQUEST_TRANSFER, AGREE, REFUSE).  
- Moverse paso a paso sobre un grid.  
- Cooperar sin un controlador centralizado.

El entorno genera pedidos dinámicamente, gestiona adjudicaciones y supervisa el rebalanceo de carga.  
El sistema evidencia comportamiento emergente propio de los SMA.

---
```
# 📂 Estructura del Repositorio

SMA-Reparto-Urbano-TF/
│
├── notebook/
│ └── TF_SMA_TCC.ipynb
│
├── informe/
│ ├── Informe_TF_SMA.pdf
│ ├── Informe_TF_SMA.md
│ └── imagenes/
│ ├── Aspose.Words.xxxxxxxx
│
└── README.md

---
```
# ⚙️ Tecnologías Utilizadas

- Python 3.10+
- Matplotlib
- Numpy
- Google Colab / Jupyter Notebook
- GitHub – Control de versiones
- Mermaid (para diagramas en Markdown)

---

# ▶️ Ejecución del Notebook

1. Abre el notebook principal:  
   **[`TF_SMA_TCC.ipynb`](./notebook/TF_SMA_TCC.ipynb)**  
2. Ejecuta todas las celdas en Google Colab o Jupyter.  
3. Al finalizar podrás observar:  
   - Métricas numéricas  
   - Log del comportamiento de un agente  
   - Gráficos de distribución  
   - Estado final del mapa  
   - Animación paso a paso 

---
