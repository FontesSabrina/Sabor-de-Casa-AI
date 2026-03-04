 Sabor da Casa IA: Pipeline Marmitex com IA
Este projeto foi desenvolvido como parte de um desafio de código da DIO (Digital Innovation One). O objetivo é criar um pipeline ETL (Extract, Transform, Load) que utiliza Inteligência Artificial para personalizar o marketing de um restaurante.

🚀 Sobre o Projeto
O sistema automatiza o processo de entender as preferências dos clientes e gerar recomendações altamente personalizadas, utilizando o poder do GPT-4.

🛠️ Tecnologias Utilizadas
Python: Linguagem principal do projeto.

Pandas: Manipulação e análise estruturada de dados.

OpenAI API (GPT-4): Inteligência Artificial para geração de conteúdo criativo.

Excel/CSV: Fontes de dados para entrada e saída.

🔄 Fluxo do Pipeline (ETL)
Extração (Extract)

Leitura do arquivo clientes_sabor_de_casa_ai.xlsx.

Base com dados de nome, cidade, perfil alimentar e prato favorito de 10 clientes.

Transformação (Transform)

Prompt Engineering: Construção de prompts estratégicos para que a IA gere mensagens no tom de voz ideal para o negócio.

Tratamento de Erros: Código preparado para lidar com falhas de conexão ou limites da API.

Carregamento (Load)

Exportação das mensagens geradas para um novo arquivo: resultado_final_sabor_de_casa.xlsx.
