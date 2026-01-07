🎁 GoGift - E-commerce de Gift Cards

O GoGift é uma plataforma de e-commerce inovadora focada na simplificação da venda e gestão de cartões-presente (gift cards). Nosso objetivo é democratizar o acesso a essa tecnologia, permitindo que qualquer empresa, independente do tamanho, possa criar, gerir e vender seus próprios gift cards de maneira fácil, rápida e intuitiva.
⚠️ Informação Importante sobre este Repositório

Este repositório específico está sendo utilizado apenas para o armazenamento da versão estável do código.

O desenvolvimento ativo, incluindo todo o histórico de commits, ramificações (branches) e evolução detalhada do sistema, está concentrado no repositório principal:

🔗 Acesse o Repositório Original - PI2025
🚀 Sobre o Projeto

A plataforma GoGift resolve a complexidade logística de empresas que desejam emitir créditos digitais. Com uma interface intuitiva, o lojista consegue configurar um novo produto em minutos, enquanto o cliente final desfruta de uma experiência de compra segura e fluida.
Principais Funcionalidades:

    Painel da Empresa: Cadastro e gerenciamento simplificado de gift cards.

    Compra Intuitiva: Fluxo de checkout otimizado para o usuário final.

    Integração de Pagamentos: Suporte a transações via Mercado Pago.

    Segurança: Autenticação robusta e proteção de dados sensíveis.

    IA Assistente: Chatbot integrado para suporte e dúvidas (utilizando LangChain e Ollama).

    Notificações: Sistema automático de e-mails para confirmação de pedidos e entrega de códigos.

🛠️ Tecnologias Utilizadas

O projeto utiliza uma stack moderna e escalável:

    Frontend: Angular (Interface SPA moderna e responsiva).

    Backend: FastAPI (Python) para uma API de alta performance e assíncrona.

    Banco de Dados: MySQL com SQLAlchemy como ORM.

    Inteligência Artificial: LangChain e Ollama para processamento de linguagem natural.

    Integrações: Mercado Pago (Pagamentos) e FastAPI-Mail (Comunicação).

📂 Estrutura do Repositório
Plaintext

├── Client/      # Código fonte da aplicação Angular (Frontend)
├── Server/      # Código fonte da API FastAPI (Backend)
├── .env.example # Modelo de variáveis de ambiente
└── run.py       # Script de automação para inicialização do projeto

⚙️ Como Executar (Breve Resumo)

    Backend:

        Navegue até a pasta Server.

        Crie um ambiente virtual: python -m venv venv.

        Instale as dependências: pip install -r requirements.txt.

        Configure o arquivo .env.

        Execute via run.py ou uvicorn app.main:app.

    Frontend:

        Navegue até a pasta Client.

        Instale as dependências: npm install.

        Inicie o servidor de desenvolvimento: ng serve.

Este projeto foi desenvolvido como parte de um Projeto Integrador (PI) focado em soluções práticas para o mercado digital.
