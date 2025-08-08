# CriptoAgente - Dashboard Frontend

CriptoAgente é um agente do mercado financeiro de criptos, com um dashboard interativo para monitoramento de predições e operações realizadas no mercado futuro da Binance. O sistema usa análise preditiva com **Machine Learning** (ML) e **Deep Learning** (DL) para automatizar as entradas no mercado.

## Arquitetura

- **Frontend**: Construído com **React**, utilizando **Redux** (ou Context API) para gerenciamento de estado, e **Chart.js** para visualizações de dados preditivos.
- **Backend**: Usando **Python** com **FastAPI** para a API e **Kafka** para mensageria em tempo real.
- **ML/DL**: Treinamento do modelo preditivo usando **Google Colab**, integrando com o backend para inferência em tempo real.
- **Banco de Dados**: **PostgreSQL** para armazenar transações e predições.
- **Mensageria**: **Kafka** para comunicação entre microserviços.

## Tecnologias Utilizadas

- **React** - Framework para criação da interface do usuário.
- **Redux/Context API** - Gerenciamento de estado global.
- **Chart.js/Recharts** - Visualização de dados em gráficos.
- **Axios** - Comunicação com a API do backend.
- **SCSS** - Estilos modulares e escaláveis.
- **Webpack** - Empacotamento do código.

## Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/criptoagente-frontend.git
   cd criptoagente-frontend
